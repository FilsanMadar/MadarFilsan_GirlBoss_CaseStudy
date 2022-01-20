# MadarFilsan_GirlBoss_CaseStudy
Technical Requirements:

Name the application: LastnameFirstname_ProjectName_CaseStudy
Use Tomcat as the web server
Views:
Use an external CSS stylesheet (internal styling may be used along with frameworks such as Bootstrap, but you must still include and utilize a custom CSS external file)
Your app should include 6 different views/pages (wireframes of the pages should be submitted with the project)
Use HTML to layout the pages along with Jakarta/Java Server Pages (JSP) to make the pages dynamic (frameworks such as Thymeleaf, Angular or React may be used as well but will not be covered in the course. The presentation of the application must meet the general view requirements.)
Use CSS to style the web pages
Use at least one JavaScript script linked from an external script file (internal scripts may be used along with frameworks such a jQuery, but you must still include and utilize a custom JavaScript external file)
Include a navigation section that is included across multiple pages
Models and Database:
Configuration file must be set up correctly (e.g., persistence.xml or application.properties)
Include at least three custom queries
Test each custom query created in each repository
Test at least one method in each of the service classes
Include at least one parameterized test
Include at least one test suite
Use MariaDB
Have at least four models along with tables in a relational database (if four models/tables do not make sense for you application, discuss this with your instructor)
Include a schema diagram of the tables
Use Jakarta Persistence API (JPA) directly or through Spring Data JPA
Include and implement repository and service classes/interfaces
Models should be annotated for binding using Spring data binding through Jakarta and/or Hibernate validation
Your application should include at least one example of each of the CRUD operations
Use JUnit to perform unit tests on the JPA repositories/services
Spring
Use Spring MVC or Spring Boot to implement the project
Include at least two ways of creating a managed bean/object
Use correct implementation of dependency injection with appropriate use of the @Autowired annotation
Include at least one example of session management (Spring Security can be used for session management)
Apply exception handling where required by the code
Include sign up and login functionality with encrypted passwords using bcrypt (use of Spring Security will satisfy this requirement)
Custom exceptions - create and implement at least one custom exception
The project package structure should be as shown in class where the models, dao/repositories, services, controllers, exceptions, etc. have a package. Views or templates don’t require a package.
Standard Java naming conventions should be followed:
Classes should be written in Pascal case
Variables, methods and URLs should be written in camel case
Files, including view files, should be written in snake case
Packages should be in all lowercase with each word separated by dots (.)
Packages should include the name of your project and your name (e.g., “org.johndoe.myprojectname”)
Each class should include comments to describe the class and the methods (see Java - JavaDoc discussion topic in Canvas)
Have the project hosted on GitHub with a “readme” file documenting user stories and technical challenges along with how the latter were resolved
 

Optional features for extra credit:

Implement Spring Security +5 points
Implement an authorization feature for special user types such as “admin” + 3 points
Create and utilize Utilities class or Enum to hold constant variables (e.g., queries, named queries, HTML pages, URL patterns, etc) + 2 points
Include a Selenium test +3 points
Implement mocking in a unit test + 2
Use web services (at least provider or consumer or both) + 10 points
