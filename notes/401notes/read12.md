# Reading

## Spring guide: Accessing Data with JPA

1. Query methods in Spring Data JPA are defined in the repository interface. The method name itself describes the query to be executed. 
For example, a method named findByLastName(String lastName) will execute a query that finds entities based on the lastName attribute. 
The implementation of these methods is provided by Spring Data JPA automatically.

2. To complete the Spring guide on accessing data with JPA, you will need the following dependencies: Spring Boot Starter Data JPA, 
Spring Boot Starter Thymeleaf, and Spring Boot Starter Web.

3. The annotations used to specify an auto-generated identification number for an Entity in Spring Data JPA are @Id and @GeneratedValue.

## Baeldung?

1. Among the Spring Data Repositories covered in the readings, the JpaRepository has the most methods available to it. 
This is because it extends PagingAndSortingRepository and CrudRepository, inheriting the methods of both.

2. A downside of using Spring Data Repositories is that it couples your code to the library and its specific abstractions, 
such as Page or Pageable. This can expose internal implementation details. Additionally, by extending repositories like 
CrudRepository, a complete set of persistence methods is exposed at once, which may not be desirable in situations where 
more fine-grained control over the methods is needed.

3. To define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository, 
you would define a method in the StudentRepository interface like this: Student findByName(String studentName);. The implementation 
of this method is provided by Spring Data JPA automatically based on the method name.
