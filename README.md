# ExpenseTracker

swaggerui link:http://13.49.220.202:8080/swagger-ui/index.html#/

User controller has 4 methods:

Localhost:8080/api/v1/user/getUser 
This api gets user data from the database


2.Localhost:8080/api/v1/user/signIn
This api save all the user datain the database

3.Localhost:8080/api/v1/user/logIn
this api is usefuil in logging the user

4.Localhost:8080/api/v1/user/deleteUser
This api deletes the user from the database

Product controller has 4 methods:
1.Localhost:8080/api/v1/product/createProduct
This api adds product details to the database

2. Localhost:8080/api/v1/product/getProducts
This api returns all the products from the database

3. Localhost:8080/api/v1/product/deleteProducts
This api deletes the products from the database

4.Localhost:8080/api/v1/product/updateProducts
This api updates the product details provided as request body

5.Localhost:8080/api/v1/product/getdate
This api returns all the expenses on a particular date

6.Localhost:8080/api/v1/product/getexp
This api returns total expenditure of a user in a particular month.

Data structure used: List

Flow:

Once the api is hit with respective data. Controller will contact service class and executes respective methods. From service method, it contacts respective repository and performs necessary action and returns the resukt to the controller

Technology used: 1 springboot 2 java 3 Aws 4. Sql

The jar file was created and uploaded into aws and deployed in the cloud.
