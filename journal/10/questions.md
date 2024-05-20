# CSharp and SQL Fundamentals
01. What is the purpose of a `namespace`?

  > A namespace is comparable to exporting and importing each class individually in Node. The difference is that the namespace helps to control the scope of where the methods in that file can be implemented within the application.

02. What is the difference between a `class` and an `interface`?

  > An interface is a base that classes can be based off of. It will include declarations of methods and properties, but not code to implement, or activate those methods. Interfaces can be inherited by multiple classes, and classes can inherit multiple interfaces.

03. What is the method that returns an instance of a class, yet it has no return type?

  > A constructor returns an instance of a class ("new Recipe") but has no return type.

05. In the Car example what is the access modifier of the `Start()` method?

  ```c#
  abstract class Car
  {
    public string Start()
    {

      return "Vroooom";

    }
  }
  ```

  > The access modifier is "public". This means that the method is available to be called from outside this class.

06. In the Car example what is `string` an indication of?

  > It indicates that this method will return something with a "string" datatype.

07. In the Car example what is `abstract` preventing?

  > "abstract" prevents the class "Car" from being made independently through the API. It is a set of properties that other classes share, and can be inherited from the car class.

08. In a SQL table, what is the difference between information in a row and information in a column?

  > Rows are instances of the model, and columns are properties of those instances. For example, columns might be "make", "model", "year". A row in that table would be a car with its properties defined by the columns.

09. Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

  > CREATE TABLE characters (
    id INT NOT NULL AUTO_INCREMENT primary key,
    name VARCHAR(255) NOT NULL,
    age VARCHAR(255),
    description VARCHAR(255),
  )

10. In SQL how can you query more than a single table? Provide an example.

  > | ANSWER HERE |
