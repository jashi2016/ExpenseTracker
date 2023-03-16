
# Expense Tracker

The expense tracker made with Java and Spring is a software application that allows individuals and businesses to track their expenses efficiently. It uses the Java programming language and the Spring framework to provide a user-friendly interface and robust tracking capabilities. The application allows users to input their daily expenses, categorize them, and generate detailed reports to analyze their spending habits. It also includes security features to protect user data and provides real-time updates on account balances. The application is highly customizable, allowing users to tailor it to their specific needs and preferences. Overall, the expense tracker is an essential tool for anyone looking to manage their finances effectively.




## Controllers
#### UserController
This controller provides various apis to perform differenet operations on user repository
![user1](https://user-images.githubusercontent.com/49145285/225577329-facd7793-e0d0-4343-bc7a-bb7e29d106ac.png)


#### ProductController
This controller provides various apis to perform differenet operations on product repository
![Screenshot 2023-03-16 150946](https://user-images.githubusercontent.com/49145285/225577467-df4848fc-3075-4cfb-9b58-587a1badb072.png)
![Screenshot 2023-03-16 151014](https://user-images.githubusercontent.com/49145285/225577602-b06710a6-61a4-4332-93b9-3ef9e873acdb.png)

## Repository
It has user and product repositories which helps to fetch data from database in an efficient manner
![Screenshot 2023-03-16 151852](https://user-images.githubusercontent.com/49145285/225579531-e3837e30-de7f-4a45-83de-de1d940c909a.png)
![Screenshot 2023-03-16 151919](https://user-images.githubusercontent.com/49145285/225579594-c8b95068-ae05-45b1-89d6-50e16e4c677d.png)


## Service
It has user service and product service modules which holds the implementation behind every api created in their respective controllers
![Screenshot 2023-03-16 151655](https://user-images.githubusercontent.com/49145285/225579159-4c0b619f-39b9-459e-9c44-97e8fe013c50.png)
![Screenshot 2023-03-16 151718](https://user-images.githubusercontent.com/49145285/225579175-9ac0aecd-5dc2-4d2f-8c04-9f83500ed4ae.png)


## Model
It consists of two entity classes which are blueprint for the user and product which are responisble for the different fields they hold.
![Screenshot 2023-03-16 151054](https://user-images.githubusercontent.com/49145285/225578214-f89bab05-f4fa-4001-b75d-848b3edb2541.png)
![Screenshot 2023-03-16 151118](https://user-images.githubusercontent.com/49145285/225578232-88f39e70-273c-4ce7-a3e6-e0dc2fe8a38a.png)

## DataFlow
The follwing flow diagram depicts the data flow of the application
![Screenshot 2023-03-16 151357](https://user-images.githubusercontent.com/49145285/225578136-72cc247d-c034-46dc-b03c-f9966b2ac074.png)

##Swagger-ui implemetation:
Swagger ui was implemented and here are the samples of the controllers:
![Screenshot 2023-03-16 153240](https://user-images.githubusercontent.com/49145285/225583329-02409265-5157-4558-b927-15aa6f2258b0.png)

![Screenshot 2023-03-16 153214](https://user-images.githubusercontent.com/49145285/225583345-4cb16bbe-8f0d-43a6-bf05-0b872e9fb6e9.png)

## Tech Stack

**Programming Language:** Java

**Server:** AWS EC2

**Frameworks/Libraries:** SpringBoot, Spring Data Jpa

**Database:** MySql

**Data Structures Used:** List from Java.utils;
