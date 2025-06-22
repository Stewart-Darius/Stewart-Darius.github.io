# Enhancement 3: Databases

The artifact I selected for the Databases category is the same Spring Boot secure server application from CS-305. Originally, the application accepted user input, generated a SHA-256 hash, and returned it via HTTPS, but lacked any form of persistence.

As part of this enhancement, I integrated a SQLite database to store the original input, the resulting hash, and a timestamp. This transformation shifted the project from a stateless utility to a functional backend system. I used JDBC for database interaction and implemented the DAO (Data Access Object) pattern to manage data transactions in a clean and modular way.

This enhancement demonstrates my skills in SQL schema design, secure data storage, and database integration in Java applications. I validated the implementation through endpoint testing and ensured the schema supported future features such as user authentication or log analysis.

One of the challenges I encountered was debugging database connection failures and error propagation in Spring Boot. By adding logging and modularizing the database logic, I resolved these issues and strengthened the application’s reliability.

This enhancement helped me practice real-world skills involving embedded databases, modular data access layers, and persistence of sensitive data in a secure context.
