# Answers to Web Development Questions

## Q1. Role of Frontend (FE)

The frontend is the part of a website that users see and interact with in their web browser. It includes things like buttons, text, images, and forms. When working on the frontend, the main goal is to make the website user-friendly and easy to navigate.

### User Interface (UI)
The user interface is related to the appearance of the website. HTML is used to create the structure, CSS is used for styling, and JavaScript is used to make the website interactive. A good UI should be simple and clear so users can easily understand it. Responsive design is also important so the website works properly on mobile phones, tablets, and desktops.

### User Interaction
JavaScript is mainly used to handle user actions such as clicking buttons, submitting forms, or hovering over elements. For example, when a user clicks a button and new content loads without refreshing the page, that is handled by the frontend. Frameworks like React or Vue make it easier to manage these interactions.

### Communication with Backend
The frontend communicates with the backend to send and receive data. When a user submits a form, the frontend sends the data to the server and then displays the response. It also shows error messages if something goes wrong.

---

## Q2. Role of Backend (BE)

The backend works behind the scenes of a web application. Users do not see it directly, but it is responsible for making sure everything works correctly.

### Server-side Processing
The backend handles the main logic of the application. For example, in an online shopping website, it processes orders, checks payments, updates product details, and sends confirmation messages.

### Database Handling
The backend manages data using databases. It can work with SQL databases like PostgreSQL or NoSQL databases like MongoDB. It performs operations such as storing, updating, deleting, and retrieving data.

### Security and Authentication
The backend is responsible for security. It manages user login, authentication, and access control. It also protects the application from attacks by validating inputs and preventing issues like SQL injection.

---

## Q3. Business Logic

Business logic refers to the rules that control how an application behaves. These rules are based on real-world requirements and decide how data is processed.

### Examples of Business Logic

1. **E-commerce Discounts**  
   An online store may apply discounts based on the number of items purchased or user type.

2. **Banking Limits**  
   A banking application may set daily withdrawal limits depending on the account type.

3. **Hotel Booking Rules**  
   A hotel booking system may have rules for pricing and cancellation policies.

These rules are usually handled in the backend to keep the application consistent.

---

## Q4. Client–Server Model

The client–server model is a basic concept used in web applications.

### Client
The client is usually a web browser or mobile application used by the user. It sends requests to the server and displays the response.

### Server
The server receives requests from the client, processes them, and sends responses back. It may also interact with databases.

### Communication Process
1. The client sends a request  
2. The server processes the request  
3. The server sends a response  
4. The client displays the result  

This model helps separate the user interface from the backend logic.

---

## Q5. Three-Tier Architecture

Three-tier architecture divides an application into three layers to make it easier to manage and maintain.

### Presentation Layer
This layer is the frontend that users interact with.

### Application Layer
This layer contains the backend logic and processes requests from the frontend.

### Data Layer
This layer manages the database and handles data storage.

### Advantages of Three-Tier Architecture
- Easy to maintain  
- Better security  
- Easy to scale  
- Clear separation of responsibilities  

---

## Q6. JavaScript as a Backend Language

JavaScript can also be used on the backend using Node.js.

### Performance
Node.js works in a non-blocking way, which helps handle multiple requests efficiently.

### Ecosystem
JavaScript has a large ecosystem of libraries available through npm, which makes development faster and easier.

### Popular Backend Frameworks
- Express.js  
- NestJS  
- Koa  
- Fastify  

Using JavaScript for both frontend and backend makes development easier because the same language is used throughout the application.
