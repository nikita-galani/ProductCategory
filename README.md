# ProductCategory
This project is a Spring Boot-based RESTful API that manages Categories and Products with a one-to-many relationship. It uses JPA with Hibernate and a relational database for persistence. The application supports CRUD operations like insert ,update ,delete and can also see all the product details for both entities, server-side pagination, and nested responses for product details.

In this application ,Category CRUD operation are

1.http://localhost:8080/api/categories?page=3-> GET all the categories

2.http://localhost:8080/api/categories-POST -> create a new category

3.http://localhost:8080/api/categories/{di}-> GET category by Id

4.http://localhost:8080/api/categories/{di}-> PUT - update category by id

5.http://localhost:8080/api/categories/{di}-> DELETE - Delete category by id

Product CRUD operation.

1.http://localhost:8080/api/products?page=2-> GET all the products

2.http://localhost:8080/api/products-> POST - create a new product

3.http://localhost:8080/api/products/{di}->GET product by Id

4.http://localhost:8080/api/products/{di}->PUT - update product by id

5.http://localhost:8080/api/products/{di}->DELETE - Delete product by id

OneToManyRelationRestApi/README.md at main · nikita-galani/OneToManyRelationRestApi 
