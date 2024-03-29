# CSharp and SQL Fundamentals

1.  What is the purpose of a `namespace`?

> To specify if its a service, controller, or repository file.

2.  What is the difference between a `class` and an `interface`?

> A class contained variables and methods while the interface is like an abstract class that can be inherited.

3.  What is the method that returns an instance of a class, yet it has no return type?

> A void method doesn't require a return type

5.  In the Car example what is the access modifier of the `Start()` method?

```c#
abstract class Car
{
  public string Start()
  {

    return "Vroooom";

  }
}
```

> The access modifier in this method is the string

6.  In the Car example what is `string` an indication of?

> An return

7.  In the Car example what is `abstract` preventing?

> Prevents it to be inherited.

8.  In a SQL table, what is the difference between information in a row and information in a column?

> The information in the column hold the values in the same branch. While rows belong to different branch of the table or a single value.

9.  Demonstrate the necessary SQL for creating a table called `characters` with the values `name, age, description` as strings, and an `int` id.

> CREATE TABLE characters (

    id INT NOT NULL PRIMARY KEY AUTO_INCREMENT,
    name VARCHAR(50) NOT NULL,
    age VARCHAR(100) NOT NULL,
    description(255) NOT NULL,

)

DROP TABLE characters;

10. In SQL how can you query more than a single table? Provide an example.

> Using the JOIN methods, allowing to query more than one table.
> CREATE TABLE students;
> CREATE TABLE teachers;
> SELECT \* FROM students, teachers
