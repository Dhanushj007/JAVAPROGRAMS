# Advanced Java Lab Programs

A collection of Java practice programs and lab examples, including core Java exercises and small desktop, database, and web applications. The projects are organized as separate examples rather than one combined application.

## Repository layout

- `Java week 1 programs/` - introductory Java examples such as variables, classes, and simple calculations.
- `Lab Programs/` - Java lab exercises.
- `Program/` - algorithms and number problems, plus Eclipse projects:
  - `JAVASWING/` - a Java Swing example.
  - `JDBCExample1/` - JDBC examples for working with a database.
  - `Demo2/`, `ServletDemo/`, and `StudentRegistrationApp/` - servlet-based web examples.
  - `DemoJSP1/` and `DemoJSPTags/` - JSP examples.
  - `SpringDemo/` - a Spring application-context example.
  - `Servers/` - Eclipse/Tomcat server configuration.

## Requirements

- A Java Development Kit (JDK) installed and available on your `PATH`.
- Eclipse IDE is recommended for the included Eclipse projects.
- Additional server or database setup may be needed for the web and JDBC examples.

## Compile and run a standalone program

For example, to run the binary search exercise from the repository root:

```sh
javac -d out Program/BinarySearch.java
java -cp out BinarySearch
```

Replace `Program/BinarySearch.java` and `BinarySearch` with the source file and class name of another standalone program. Some examples read input from the console.

## Working with the Eclipse projects

Import an individual project under `Program/` into Eclipse as an existing project, then configure the required Java version and any project-specific libraries or server runtime. The Servlet and JSP applications need a compatible servlet container. The JDBC examples require a configured database and JDBC driver.

## Notes

- There is no single build command for the entire repository; compile, run, or deploy examples individually.
- Generated `.class` files may be present alongside source files. The `.java` files are the editable source.
