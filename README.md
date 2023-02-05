# Webapp for booking an appointment

In this full-stack project, we will learn how to develop a simple full-stack web application that is a basic Banking Appointment Application using React, Spring Boot, RestAPI and SQL Database.

The back-end server uses Spring Boot with Spring Web MVC for REST APIs and Spring Data JPA for interacting with the MySQL database. The Front-end side is made with React, React Router, Axios & Bootstrap.

## Backend Architecture


![Architecture](https://user-images.githubusercontent.com/61236166/216466248-c00ded94-55d9-4eb0-8d96-91b5c60cd96b.png)


## Full Stack Spring Boot and React Architecture


![Screen Shot 2023-02-02 at 4 43 19 PM](https://user-images.githubusercontent.com/61236166/216466471-d9ff7418-992f-4dd6-8f40-7d604c1aade1.png)


## Objective

I have build a full stack web app for booking an appointment at a local bank to carry out various activities with CRUD features viz :
- Create Customer
- Book An Appointment to a nearest branch
- List all the Upcoming appointments for a user
- Delete an appointment
- Update an existing appointment

Some basic overview of the technologies used:

- Spring Boot : Spring Boot makes it easy to create stand-alone, production-grade Spring based Applications that you can "just run". I take an opinionated view of the Spring platform and third-party libraries so you can get started with minimum fuss. Most Spring Boot applications need minimal Spring configuration. I also used Spring Boot to develop REST web services and micro services.

- React JS : It is a JavaScript library created by Facebook and it used to build user interface for the front end. It is widely used for building single-page applications and mobile applications. React uses a virtual DOM to improve performance and allows developers to easily create reusable UI components.

- RestAPI : REST (Representational State Transfer) is a software architectural style for building web services. A RESTful API (REST API) is a type of web service that follows the REST architectural style and provides a standardized way for accessing and manipulating data over the internet. REST APIs use HTTP methods (such as GET, POST, PUT, DELETE, etc.) to perform operations on resources and return responses in a format such as JSON or XML. REST APIs are commonly used to interact with web-based services and are an essential building block for many modern web applications.

## Tools and Technologies:
#### Server Side(Backend) Tools and technologies: 
- Spring Boot
- Maven
- SpringData JPA
- JDK 
- Embedded Tomcat
- MySQL Database

#### Client Side(FrontEnd) Tools and Technologies
- React
- NodeJS and NPM
- Modern JavaScript (ES6)
- Bootstrap and Axios HTTP Library
- VS Code IDE

## Below are some of the screenshots of the Database, FrontEnd and Backend

#### Backend-Spring Boot Depicting the important packages
![Screen Shot 2023-02-05 at 1 07 54 AM](https://user-images.githubusercontent.com/61236166/216806512-159a17fd-010b-46fa-83d0-5408b658aa3c.png)

#### SQL Workbench showing various tables and location database
![Screen Shot 2023-02-05 at 1 12 52 AM](https://user-images.githubusercontent.com/61236166/216806571-5a838654-6577-493a-bc93-d05b6b94aeec.png)

#### The homepage of the webapp
![Screen Shot 2023-02-02 at 3 24 41 PM](https://user-images.githubusercontent.com/61236166/216806601-98b1ec19-6d77-425b-9f80-c1664d4cb21c.png)

#### Navigation Bar offering variety of other features
![Screen Shot 2023-02-02 at 3 24 56 PM](https://user-images.githubusercontent.com/61236166/216806624-7ae082b6-045c-405c-9ef2-90082b244bd6.png)

#### Meeting scheduling page where user enter his/her details
![Screen Shot 2023-02-02 at 3 25 04 PM](https://user-images.githubusercontent.com/61236166/216806798-7985906f-9831-48fe-b779-3040d0f7bf62.png)

#### Option to choose the nearest branch from client's current location
![Screen Shot 2023-02-02 at 3 25 48 PM](https://user-images.githubusercontent.com/61236166/216806824-f2d560b7-64d2-4679-a5ea-afca7e538038.png)

#### Date and Time Selection Page
![Screen Shot 2023-02-02 at 3 25 55 PM](https://user-images.githubusercontent.com/61236166/216806892-a3b3d60a-e61e-4c18-bdfc-2ebcae0c410b.png)

#### Appointment Confirmation Page- Customer can check all the appointments and even modify or cancel one
![Screen Shot 2023-02-02 at 3 26 31 PM](https://user-images.githubusercontent.com/61236166/216806927-6c97f4e4-4306-4796-b667-f0906e0027ea.png)

## How To Run The Project

- Please clone or download both the folders from the repository.
- Open IntelliJ IDE on your laptop/desktop.
- Load the folder bank_appointment (This has the backend code in it and for the frontend, I have used another directory named FrontEnd/book-app-frontend.
- The version of Gradle, maven, JDK might be different from my project in your machine, hence download and update the dependencies accordingly.
- Once the project is up and all the dependencies has been downloaded, please navigate to src/main/resources/application.properties.
- Once you are there, you will need to change the username and password of the datasource and put the one that you use to login to your My SQL Workbench.(This connects your backend to your local database and store and retrieves the data from the local database)
- Make sure the name of the database is banking_appointment_system. If not, you can create a new database and then update the name of the database in the datasource.url.
- After editing the details, navigate to bank_appointment/src/main/java/com.bank_app.bank_app/service/BankAppApplication and run the main class. Voila, your server should be up and running. Some of the tests you can do is connect to your database and you should be able to see location data. You can also check if the backend is running smoothly and data is being transmitted to the database via API calls using Postman(or any other API test tool).
- Below is a screenshot of a connection being successfully established.
![Screen Shot 2023-02-05 at 1 40 46 AM](https://user-images.githubusercontent.com/61236166/216807446-95a7ec99-5fca-4bf7-8036-b96a091732a0.png)

- Once the backend is up and running, now we will move to the front end. For frontend, I suggest you to use Visual Studio Code or VS Code as IDE.
- Open the folder FrontEnd/book-app-frontend. 
- This step is not necessary, but I would recommend you to delete the directories node_modules by navigating to FrontEnd/book-app-frontend/node_modules and package-lock.json. As these are directories which contain dependencies packages like react , react-dom etc. The version might mismatch or one of million other things might happen. Hence, deleting these directories will help you setup the project in the right manner.
- Once done, open the terminal window in the IDE.
- Now, we will install all the dependencies and set up the React Environent on your system for the project to run successfully.
- Type npm install
- Then type npm install react-scripts
- Now, all the dependencies are downloaded and you are ready to run your react app. Type npm start in the same terminal.
- Your browser should open http://localhost:3000/ and your webapp must be up and running.
PS- If you face any bugs or errors while running the project, you can paste your error at https://stackoverflow.com/ . This website was really helpful to come across the mistakes I made while building this project.

### You can email me if you have any other question or queries. Hope you enjoy navigating through the project.






