# Reading

## One to Many relationships, in software... specifically.

1. Name a few examples of real world ManyToMany relationships.

  - A student can be enrolled in multiple courses, and a course can have multiple students.
  - A doctor can have multiple patients, and a patient can have multiple doctors.
  - A book can have multiple authors, and an author can write multiple books.

2. Explain the significance of a join table for ManyToMany relationships.

A join table is used to manage and map the relationship between the two entities. It holds the foreign keys of both entities and acts as a bridge between them. 
This table is necessary because relational databases do not directly support many-to-many relationships. The join table effectively breaks down the many-to-many 
relationship into two one-to-many relationships, which are easier to manage and understand.

3. What are the values held within a join table?

A join table typically contains the foreign keys of the two entities that are involved in the many-to-many relationship. 
These foreign keys act as references to the primary keys of the respective entities. The join table may also contain additional 
attributes related to the relationship, if necessary.

## Security 

1. According to the author of the article, will you ever be truly secure from ALL possible security threats?

  - It is impossible to be truly secure from all possible security threats. He argues that the complexity of modern systems and the unpredictability of user behavior make it impossible to anticipate and protect against all potential vulnerabilities. 
