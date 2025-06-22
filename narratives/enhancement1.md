# Enhancement 1: Software Design and Engineering

The artifact I selected for the Software Design and Engineering category is a Java-based Spring Boot secure server application initially developed in CS-305. The original purpose of this artifact was to calculate SHA-256 hashes of user input and return the result via a REST endpoint over HTTPS. However, the original version lacked modularity and industry-standard architecture patterns.

To address this, I enhanced the project by refactoring it into a more modular, maintainable format. Specifically, I separated logic into service and controller layers and introduced structured logging for better traceability. I also configured HTTPS using a self-signed certificate to ensure secure data transmission, following best practices for secure backend development.

These enhancements demonstrate my ability to organize code according to common software engineering design principles. By implementing modular separation of concerns, adding JavaDocs, and integrating HTTPS configuration into the Spring Boot application, I aligned this project with secure and scalable software practices. This enhancement directly supports the program outcomes related to secure design, maintainability, and clean architecture.

Through this process, I reinforced my understanding of project modularization, configuration management, and documentation standards. It also gave me the opportunity to work with Java 17-specific tooling and troubleshoot HTTPS configurations through Spring Boot's built-in capabilities.
