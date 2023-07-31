# Reading

## Spring Security overview

1. What does it mean to authenticate a user?

Authentication is the process of verifying the identity of a user. This is typically done by asking for credentials such as a username and password. The system checks if the entered credentials match the ones stored in its database. If they match, the user is authenticated.

2. What does it mean to authorize a user?

Authorization is the process of giving an authenticated user permission to access specific resources or perform certain actions. For example, an admin user might be authorized to access all parts of a system, while a regular user might only be authorized to access a subset of the system.

3. What are the three possible outcomes of the AuthenticationManager’s authenticate() method?

  - The AuthenticationManager's authenticate() method in Spring Security can have three possible outcomes:
      + Returns an Authentication (normally with authenticated=true) if it can verify that the input represents a valid principal.
      + Throws an AuthenticationException if it believes that the input represents an invalid principal.
      + Returns null if it cannot decide.
