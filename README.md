# Employee-Manager FullStack Application

- **Front-end Component** using **React** is located here: https://github.com/ishrivasayush/Employee-Manager/tree/main/employee-management-system-ui
## Contents
1. [ Brief Summary ](#summary)
2. [ Aims and Motivation ](#aims)
3. [ Technologies, Requirements and Software Tools ](#tech)
4. [ Design ](#design)
5. [ Application Screenshots ](#demo)

<a name="summary"></a>
## Brief Summary
- I developed a **RESTful API** using **Spring Boot and MySQL for the back-end**, tested it with **Postman**, and integrated it into a **React front-end using axios**.
- **CREATE, READ, UPDATE and DELETE (CRUD)** appliction.
- This repository contains the **back-end** of a **Full Stack** **personal project**, which is **responsible for storing employee information** and is implemented using the **Spring Boot Java Framework** which serves as the **web framework** for the **back-end**.
- This application allows users to **view, add, remove, and edit** individuals within their management system.
- This project is now **fully utilised** by my **community's sports club**.
<a name="aims"></a>
## 🎯Aims and Motivation
- The main objective of this project was to create a thorough **Full Stack Application** using **Spring Boot & MySQL** as the **back-end** and **React** as the **front-end**.
- Driven by an **unwavering enthusiasm** for **learning and self-improvement**, I dedicated my **personal time** to meticulously **develop and refine this Full Stack Application**.
<a name="tech"></a>
## ⚙️Technologies, Requirements and Software Tools
- Requirements listed below are for the **front-end and back-end**.
### Programming and Scripting Languages
- Java
- JavaScript
- HTML
- CSS
- JSON
### Frameworks & Libraries
- Spring Boot - **Back-end**
- React - **Front-end**
- Tailwind - **Front-end & Back-end**
### npm Requirements (React)
- nmp axios
- npm react-router-dom
### Other Software Tools
- **MySQLWorkbench** played a role where the **back-end** relied on this technology to **store user information**.
- **Postman** was used to **test PUT, GET, POST and DELETE requests to the database**.
<a name="design"></a>
## ✏️Design - Back-end
### Back-end Technology Stack
- **Java** served as the **back-end programming language** for the web application, while the **Spring Boot framework** was employed to **facilitate its development and operation**.
- **Spring Boot** was utilised to **create user models**, which were subsequently employed to **store employee information in the database**. The user models were established using the **Jakarta Persistence import** and **annotations**, including **@Entity, @Id, and @GeneratedValue**. This approach **facilitated the maintenance of the REST API**, making it more manageable and easier to maintain in the long run.
- **MySQL Workbench and DataGrip** were employed to **store employee information**. The **back-end**, developed with **Spring Boot**, was **configured to connect with the database**, while the **front-end**, built with **React**, was responsible for **retrieving and displaying** this information.
- **Spring Boot** was additionally utilised to **create custom exceptions**, specifically designed for **handling scenarios where the user ID was not found or encountered other exceptional conditions**.
#### React & Spring Boot Summarisation Diagram

![spring-boot-react-crud-example-rest-api-architecture](https://github.com/Saad1929/Employee-Management-System/assets/108022733/9951b53f-cf9c-4bf8-830f-654fa135789f)


### Postman and Testing Sceenshots
- **Postman** was used as an **API platform** to **design, build, test and iterate** the **RESTful API** which was **built using Spring Boot**.
- Requests were dealt in **JSON** and **SQL**.
#### GET Request (Normal Case) 
<img width="800" alt="GET" src="https://github.com/Saad1929/Employee-Management-System/assets/108022733/6f37bf38-071f-4d61-b4a7-7569e4730129">


#### PUT Request (Normal Case)
<img width="1440" alt="PUT" src="https://github.com/Saad1929/Employee-Management-System/assets/108022733/2d978d20-75d9-43a1-96e2-d05f067df848">


#### POST Request (Normal Case)
<img width="800" alt="Get   Post" src="https://github.com/Saad1929/Employee-Management-System/assets/108022733/ada4d1d1-fc66-4223-ac29-434f0d8fc446">


#### Postman Summarisation Diagram
![postman](https://github.com/Saad1929/Employee-Management-System/assets/108022733/e045a6d9-48a6-46d8-8c78-daa6cb444606)


<a name="demo"></a>
## Application Screenshots
### Home Page 
![Screenshot (488)](https://github.com/ishrivasayush/Employee-Manager/assets/103355440/c614be6a-4c4a-4352-99b4-ed74f49f7073)



### Register User Page
![image](https://github.com/ishrivasayush/Employee-Manager/assets/103355440/9bbedd94-db6c-4167-b359-0f7e9024bfff)


### View User Details Page
![Screenshot (488)](https://github.com/ishrivasayush/Employee-Manager/assets/103355440/a37f4fb0-e59a-4921-8d85-fad140a86596)


### Edit User Page
![image](https://github.com/ishrivasayush/Employee-Manager/assets/103355440/8085318c-2ab2-4568-99a7-469f61e84212)


