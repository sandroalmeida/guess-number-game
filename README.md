# guess-number-game

This a a good example of project using Maven and Spring Framework
Some characteristics can be listed as follow:
- This project was created using the modularize concept, so it have a primary POM file and three modules inside it.
Each module has their own POM file and all dependencies are controled by the Core module.
- This project has examples about Dependency Injection using Spring.
- This project also has a good example about how to use a property file and autowire the values using Spring annotations.
- Later in this project was added the Spring Boot configuration
- The project has 3 modules: Core, Console and Web.
The core module is the game structure and dependencies references.
The console module run the application in a console mode, sharing the core module structure.
The web modulo run the application in a web mode, also sharing the core module structure.

I built this project using the spring course on Udemy create by the instructor Tim Buchalka
