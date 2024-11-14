# Category_Product

1) GitHub Link:You can access the full project repository on GitHub here:-
https://github.com/dishajaingithu/Category_Product/tree/main

2) How did I get the code?
  * I cloned the repository using git clone.
  * I set up the project in my development environment using Visual Studio Code.
  * I installed Java and MySQL and set up the MySQL database "productcatalog_db" in MySQL Workbench.
  * I ran the Spring Boot application  mvn spring-boot:run to start the backend server on localhost:8080.

3) How did I run the machine test?
  * I implemented the required Category and Product CRUD operations with pagination.
  * Used Postman to test the API endpoints (for creating, updating, fetching, and deleting categories and products).
  * Verified the operations by checking the database updates in MySQL Workbench.
    
4) DB Design:
  * I used MySQL Workbench for the database management:
    * Category table: Contains columns id (primary key) and name.
    * Product table: Contains columns id (primary key), name, price, and category_id (foreign key referencing Category).
    * The Product table has a many-to-one relationship with the Category table.
