# TaberNota

TaberNota is a restaurant terminal and ordering system designed to address the inefficiencies in the current market. It 
aims to enhance operational efficiency for restaurant workers while improving the overall customer experience. This 
project was developed as part of a class assignment, leveraging modern web technologies to create a seamless solution 
for restaurants.

## Table of Contents
- [Application Overview](#application-overview)
- [Objective Audience](#objective-audience)
- [Market Analysis](#market-analysis)
- [Key Functionalities](#key-functionalities)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [License](#license)

## Application Overview

The goal of TaberNota is to improve outdated and user-unfriendly restaurant terminal systems by offering a more 
intuitive and efficient solution. Current systems in the market often create bottlenecks in workflows, leading to 
delays in order processing and payment management. TaberNota solves these issues with a user-friendly interface, 
client-side payment functionalities, and a backend system that ensures real-time updates and smooth operations. This 
project also supports offline functionality and cloud data syncing for improved reliability.

## Objective Audience

This application is primarily aimed at the restaurant and bar industry, with a focus on businesses in the Community of 
Andalucía, Spain. TaberNota seeks to provide a competitive edge in the crowded restaurant industry by reducing 
operational inefficiencies, speeding up service times, and allowing clients to take a more active role in managing 
their orders and payments.

## Market Analysis

Existing restaurant terminal systems are often difficult to navigate and lack modern features such as client-side 
payment and analytics. TaberNota differentiates itself by offering a streamlined, easy-to-use interface, client-side 
payment options (including bill splitting), and robust analytics for improving business performance.

## Key Functionalities

### 1. **Handle Ordering**
- Servers can manage and place orders quickly and intuitively.
- Customizable user roles (servers, managers, kitchen staff) with tailored permissions.

### 2. **Allow Payment**
- Clients can pay their bills directly through the app, using features like QR code scanning.
- Servers and managers have full control over payment management.

### 3. **Track Worker Hours**
- The system automatically logs work hours for each user, accessible by authorized roles for payroll and operational 
insights.

### 4. **Handle Inventory**
- Inventory management with features like stock alerts and automatic reordering suggestions.

### 5. **Allow and Provide Statistics**
- Detailed business statistics, including best-selling items, worker activity, and revenue per table/shift.

### 6. **UI for Workers**
- An intuitive, customizable UI for workers with features such as quick-order shortcuts and real-time updates.

### 7. **UI for Clients**
- A simple, user-friendly UI for clients to view menus, split bills, and make payments securely.

## Technologies Used

- **Programming Languages:** JavaScript (Vue.js for frontend), Java (Spring Boot for backend)
- **Libraries and Tools:**
    - **Axios:** HTTP requests for API interaction
    - **Bootstrap / Tailwind CSS:** Styling and responsive design
    - **WebSocket:** Real-time updates between kitchen, servers, and clients
    - **Firebase / AWS:** Cloud storage and data synchronization
    - **Local Storage:** Offline functionality
    - **JUnit:** Backend testing

## Installation

To get started with TaberNota, follow the steps below:

1. Clone the repository:
```bash
   git clone https://github.com/yourusername/tabernota.git
   cd tabernota
```

Install dependencies for the frontend and backend:
For the frontend (Vue.js):

cd frontend
npm install

### For the backend (Spring Boot):

```bash
    cd backend
    ./mvnw install
```

Set up the database and configure environment variables as needed. Ensure that Firebase or AWS credentials are set up 
for cloud storage.

### Run the application:

Start the backend:

```bash
    ./mvnw spring-boot:run
```

### Start the frontend:

```bash
    npm run serve
```

Open your browser and navigate to http://localhost:8080 to view the application.

### Running the Application

Make sure you have Node.js (for Vue.js) and Java (for Spring Boot) installed.
The frontend and backend are designed to run on different ports, with the frontend typically running on 
localhost:8080 and the backend on localhost:8081.

### License

This project is licensed under the MIT License - see the LICENSE file for details.



