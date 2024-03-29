# Application Architecture, MVC Design Pattern
01. What are the Pillars of Object Oriented Programming (`OOP`)?
  
  > Data Abstraction: hiding information that isn't immediately necessary, in order to make the structure and behavior more easily understood.
  Encapsulation: prevents misuse of data, and ensures proper functioning of methods by limiting access and bundling related data and methods together.
  Inheritance: ability to create a new class from an existing class, typically maintaining the attributes of the parent class.
  Polymorphism: the ability of an object to take on multiple forms.

02. How does `export` differ from `export default`?
  
  > Regular "export", or "named export", is used when exporting several values from one module. These will each need to be imported into the other modules that want to use them.

  A default export can only be used once on a module. It can be used to include several elements in one export. It can include functions, classes, objects, or anything else.

03. What is Encapsulation?
  
  > Encapsulation is a way of bundling data so that it is only visible to other parts of the code that are specifically granted access.
  There are a few different reasons why this is important:
    • We can make small changes with small effort. If we change the name or value of something that is referenced throughout the code stack, the change is reflected all throughout. We don't need to track down every reference and change them manually.
    • Access to certain portions of an application are limited for security and stability.


04. What are some of the benefits of the `Proxy` object that we are using in our structure for applications?
  
  > This is still a little unclear to me, but it seems like Proxy objects are used in place of the "actual" objects. They seem like substitutes that report any modifications back to the original, while keeping the original in a secure location.

05. What the difference between a `class` and an instance of a `class`?
  
  > A class is like a blueprint for creating objects. Instances would be individual objects that are made using that blueprint.
  For example, we might have a class defining the pieces of information we'll collect from everyone filling out a certain form. Each person who fills it out would have their data stored as separate bundles, and those are the instances.

06. What is a computed Property?
  
  > A computed property is another name for a "getter", which is basically a template of <i>computed</i>, or <i>compiled</i> content that references the data model. It is sort of like an extension to the instances of the model, and is callable like any other property.

07. What is the purpose of the `MVC` pattern?
  
  > The MVC pattern organizes data and functionality of an application into distinct layers to carry out specific types of tasks.

08. What is the job of the `Controller` in the `MVC` Pattern?
  
  > The Controller receives inputs from the View, or the user interface, and passes instructions to the Service layer. In most cases, it will also receive modified data back from the Service to provide back to the user.

09. What is the job of the `Service` in `MVC`?
  
  > The Service gets to modify data. It receives instructions from the Controller, and calls the right data in the AppState to modify. Modification can be adding new information, removing information, or changing something to a new value.
  We as users usually want some sort of verification that what we were trying to do either did or didn't work, so the Service usually sends that information back to the Controller (or at least puts it somewhere the Controller can access) to send to View.

10. What is the job of the `Model` in `MVC`?
  
  > For our purposes, the Model has so far been used to structure data, and to inform the rest of the application what to work with.
