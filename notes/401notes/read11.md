# Reading

## Spring App Basics

1. What role do the @Controller classes play in a Spring MVC application?
- In a Spring MVC application, @Controller classes play a crucial role in handling incoming HTTP requests and returning responses.
- They are responsible for processing the data, applying business logic, and returning the appropriate view to the client.
- The @Controller annotation is used to mark a class as a web request handler.

2. Explain to a non-technical friend what a GET request is.
- Imagine you're at a restaurant and you want to see the menu, you'd have to ask the waiter. This is similar to a GET request.
- Your browser sends a GET request to a website's server (the waiter) asking for a specific webpage (the menu).
- The server then responds by sending back the webpage you asked for.

3. What annotation should be placed on your Spring Boot application class?
- The @SpringBootApplication annotation should be placed on your Spring Boot application class. This is a convenience annotation that adds all of the following:
  + @Configuration: Tags the class as a source of bean definitions for the application context.
  + @EnableAutoConfiguration: Tells Spring Boot to start adding beans based on classpath settings, other beans, and various property settings.
  + @ComponentScan: Tells Spring to look for other components, configurations, and services in the specified package, letting it find the controllers.

## Spring MVC and Thymeleaf

What method allows for a variable defined in Java (in your Spring Controller) to be dispalyed in HTML with the help of Thymeleaf?
- The method that allows for a variable defined in Java (in your Spring Controller) to be displayed in HTML with the help of Thymeleaf
is the addAttribute method of the Model class.

Explain the role of a @Controller class in a Spring MVC application.
- The role of a @Controller class in a Spring MVC application is to prepare a model map with data and select a view to be rendered.
This model map allows for the complete abstraction of the view technology and, in the case of Thymeleaf, it is transformed into a
Thymeleaf context object (part of the Thymeleaf template execution context) that makes all the defined variables available to expressions executed in templates.

What is a model attribute refered to in Thymeleaf?
- A model attribute referred to in Thymeleaf is a piece of data that can be accessed during the execution of views.
The equivalent term in Thymeleaf language is context variables. There are several ways of adding model attributes to a view in Spring MVC.
In Thymeleaf, these model attributes (or context variables in Thymeleaf jargon) can be accessed with the following syntax: ${attributeName},
where attributeName in our case is messages. This is a Spring EL expression. In short, Spring EL (Spring Expression Language) is a language
that supports querying and manipulating an object graph at runtime.

### Would you like to know more?

What even is the Model in Spring MVC? Also there's @Controller and @RestController, seems one is for rest api and the other for something else maybe?
