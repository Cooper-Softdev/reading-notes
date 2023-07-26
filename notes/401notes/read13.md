# Reading

## Related data in Spring (only read section “3. One-to-Many Relationship”)

1. Name a few real life examples of “One To Many” relationships.

  - My neighbor does this poly thing so she's got a ton of boyfriends and all them boyfriends only have one girlfriend, her. (I don't get it, but it's taking dudes out of the dating pool so that's a + for me.)
  - A teacher can have multiple students, but each student has one teacher for a specific subject.
  - A book can have multiple chapters, but each chapter belongs to one book.

2. Given two entities, one named Player and one named Team, if you wanted to create a one to many relationship with those entities which would be the one and which would be the many?

  - The Team would be the "One" and the Player would be the "Many".

3. Explain one to many relationships to a non-technical friend.

  - Imagine, if you can that we orbit a star. That star has many planets, but our planet only has 1 star. Also earth is flat.

## Spring Integration Testing

1. Describe the difference between a unit test and an integration test.

  - A unit test is a type of test that checks a small "unit" of code, usually a single function or method, in isolation from the rest of the system. It verifies that the specific piece of code works as expected.

  - An integration test, on the other hand, checks how different parts of the system work together. Instead of testing individual components in isolation, integration tests ensure that the system as a whole functions correctly when all its parts are integrated.

2. What is the object that provides support for Spring MVC Testing?

  - The MockMvc object provides support for Spring MVC testing. It allows us to execute requests against the DispatcherServlet.

3. What does the “perform()” method do in a Spring integration test?

  - The perform() method is used to send a request to the DispatcherServlet. It returns a ResultActions object which allows us to define expectations about the results. For example, we can use it to expect a certain status code, content type, or response body.
