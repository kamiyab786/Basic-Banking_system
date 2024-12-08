# Basic-Banking-System

***Basic Banking System***

This is a dynamic and user-friendly web application that simplifies money transfers between users. The application is designed with scalability and security in mind, allowing users to perform essential banking functions such as viewing user details, transferring funds, and tracking transaction histories. It is built using modern web technologies and adheres to best practices for seamless user experience and efficient database management.

---

## **Features**
- **User Management**:  
  Easily view all users, select individual profiles, and access their details.
- **Fund Transfers**:  
  Enable secure and smooth transfer of funds between users by selecting a sender and receiver.
- **Transaction History**:  
  Maintain a detailed log of all transactions, including sender, receiver, transfer amount, and timestamp.
- **Scalability**:  
  New users can be added to the system effortlessly to meet growing demands.
- **Responsive Design**:  
  The application is optimized for devices of all sizes using Bootstrap.

---

## **Technology Stack**
### **Front-End**
- HTML, CSS, Bootstrap, AngularJS

### **Back-End**
- Node.js, Express.js, MongoDB

---

## **Database Structure**
The application uses MongoDB to store and manage data:
1. **Customers Table**:  
   Stores essential user information:
   - `name`: The user's name (String).  
   - `email`: The user's email address (String).  
   - `balance`: The user's current account balance (Int32).  
   
2. **Transaction History Table**:  
   Tracks all transaction details:
   - Sender's name.  
   - Receiver's name.  
   - Amount transferred.  
   - Timestamp of the transaction.

---

## **Website Flow**
The application provides a step-by-step process for users:
1. **Home Page**:  
   Introduction to the system with navigation options.  
2. **View All Users**:  
   Display a list of all registered users.  
3. **Select and View a User**:  
   Access details of a specific user, including account balance.  
4. **Transfer Money**:  
   Initiate a fund transfer by selecting a sender and receiver.  
5. **View Transfer History**:  
   Track all past transactions with complete details.

---

## **How to Run the Project**

### **Pre-Requisites**
1. Install **Node.js**
2. Install **MongoDB** and **MongoDB Compass**

---

### **Steps to Setup**
1. **Setup MongoDB**:  
    - Connect MongoDB Compass to **`localhost`**.  
    - Create a database named **`myproject`**.  
    - Create a collection named **`sparkbank`**.  
    - Insert dummy user data with the following fields:  
      - `name` (String)  
      - `email` (String)  
      - `balance` (Int32)

2. **Run the Project**:
    - Open the project folder in **Terminal/Command Prompt/PowerShell**.
    - Run the following commands:
      ```bash
      npm init
      npm install mongoose
      npm install express
      node server.js
      ```
    - Open a browser and navigate to **`http://localhost:2800`**.

---

## **Screenshots**
### Home Page
![Home Page](https://user-images.githubusercontent.com/50388943/115108780-eff6ca00-9f8f-11eb-8aac-b8147d9abb33.png)

### View All Users
![View All Users](https://user-images.githubusercontent.com/50388943/115108781-f127f700-9f8f-11eb-98bf-44cccdf10a15.png)

### Transfer Money
![Transfer Money](https://user-images.githubusercontent.com/50388943/115108785-f84f0500-9f8f-11eb-9d7a-4e5cfd269349.png)

### Transaction History
![Transaction History](https://user-images.githubusercontent.com/50388943/115108792-000ea980-9f90-11eb-8dde-ad6c75e87ab3.png)
