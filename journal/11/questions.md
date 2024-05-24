# A bit more CSharp and SQL
1. What does ***inheritance*** accomplish for us in C#?

  > Inheritance allows us to be more efficient with writing code, but also to help establish shared structure.

2. How does ***member inheritance*** work in C#? Does a `Class` inherit all members of the base `Class`?

  > Child classes won't inherit constructors or finalizers. Everything else will be inherited, though private and internal classes won't be accessible from the child class.

3. How does ***accessibility*** affect inheritance?

  > Accessibility modifiers directly affect inheritance: a private class will not be inherited, but a public one will be.

4. What is the difference between a `PRIMARY KEY` and a `FOREIGN KEY`

  > The primary keep is the unique identifier for the model you're looking at; the foreign key is the unique identifier connecting a virtual object model.

5. What is an ***alias***?

  > An alias is similar to defining a variable, but seems to be concerned with abstracting functional bits of code as opposed to representing values.

6. Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

  ```SQL
  CREATE TABLE doctors (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patients (
    id INT NOT NULL AUTO_INCREMENT,
    -- CODE OMITTED
    PRIMARY KEY (id)
  )

  CREATE TABLE patient_doctors (
    id INT NOT NULL AUTO_INCREMENT,
    doctorId INT NOT NULL,
    patientId INT NOT NULL,

    FOREIGN KEY (doctorId)
      REFERENCES doctors(id),
    FOREIGN KEY (patientId)
      REFERENCES patients(id),
  )

  ```

  (when a doctorId has been passed)
  >   SELECT FROM
  patient_doctors.*,
  doctors.*,
  patients.*

 >  JOIN doctors ON doctors.id = patient_doctors.doctorId
  JOIN patients ON patients.id = patient_doctors.patientId
WHERE doctors.id = @doctorId;



