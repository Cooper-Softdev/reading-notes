# Reading

## nosql vs sql

SQL	NoSQL
 	 
1. What kind of data is a good fit for an SQL database? Give a real world example.
- Customer information with associated orders and invoices in an e-commerce system.
- Employee records with department information and job titles in a human resources system.

2. What kind of data is a good fit a NoSQL database? Give a real world example.
- User-generated content in a social media platform, such as posts, comments, and likes.
- Sensor data from Internet of Things (IoT) devices, where the data structure may vary based on the device type and its readings.

3. Which type of database is best for hierarchical data storage?
- SQL graph database would be best.

4. Which type of database is best for scalability?
- NoSQL databases are better for scability.

## sql vs nosql

1. What does SQL stand for?
- Structured Query Language.

2. What is a relational database?
- A relational database is a type of database that organizes data into tables with predefined relationships between them. It follows a structured data model with rows and columns, and relationships are established using primary and foreign keys.

3. What type of structure does a relational database work with?
- A relational database works with a structured data model based on tables, rows, and columns. Data is organized into tables, where each table represents an entity, and rows represent instances of that entity, with columns representing attributes.

4. What is a ‘schema’?
- A schema in the context of a relational database refers to the structure or blueprint that defines the organization and relationships of the tables, along with data types, constraints, and rules for the data.

5. What is a NoSQL database?
- A NoSQL database, or a non-relational database, is a type of database that provides a flexible data model and does not rely on a fixed schema. It allows for storing and retrieving data in various formats like key-value pairs, documents, graphs, or wide-column stores.

6. How does it work?
- NoSQL databases work by storing and retrieving data using different data models based on their specific type (e.g., key-value, document, graph). They prioritize horizontal scalability and distributed data storage to handle large volumes of data and high traffic loads.

7. What is inside of a MongoDB database?
- Inside a MongoDB database, data is stored as JSON-like documents, organized into collections. Each document can have a different structure, allowing for flexible data representation.

8. Which is more flexible - SQL or MongoDB? and why.
- MongoDB is generally considered more flexible than SQL databases because it does not enforce a fixed schema. Documents within a collection can have different structures, allowing for more dynamic and adaptable data representation.

9. What is the disadvantage of a NoSQL database?
- A disadvantage of NoSQL databases is the lack of strict data integrity and referential integrity enforcement compared to SQL databases. Data relationships are managed at the application level, requiring additional effort to ensure consistency and integrity across different documents or collections. Additionally, NoSQL databases may have limitations in complex query capabilities compared to SQL databases.
