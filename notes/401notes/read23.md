# Reading

## Rooms

1. What database engine is Room wrapped around? Do you think this is a good choice? Why or why not?
   - Room is wrapped around SQLite.
   - Yes, probably. Using Rooms should simplify the use of SQLite making it easier for developers to write their applications faster and with less hassle.

2. Do Rooms have any similarities to JPA?
   - Yes, both are an abstration layer over a database, which allows developers to interact with the databse using objects rather than a SQL query.

3. Describe a DAO in your own words
   - DAO is a Data Access Object. It's a way to abstract the direct interfacing with a database, you can have a separation of concerns to allow cleaner and more
     more modular code with reusability of the same annotations like @Query or @PrimaryKey. This also allows the code to be maintained and updated easilier. (real word)
