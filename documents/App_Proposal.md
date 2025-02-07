# Initial Idea - TaberNota

## Application Idea
The initial idea of this application is to revamp the outdated and user-unfriendly applications that currently dominate 
the market for restaurant terminal and ordering systems. These systems, while often functional, lack intuitiveness and 
efficiency, leading to interruptions or delays in workers' workflows. This inefficiency results in longer wait times for customers, reduced satisfaction, and potential financial losses for businesses due to operational bottlenecks.

In addition to the lack of user-friendly interfaces in current terminal applications, there is also a significant 
gap in client-side integration. Modern clients have access to advanced technology that could enhance their 
interaction with restaurants. For example, allowing clients to split or pay their own bills directly through an app 
would delegate these tasks to them, fostering a sense of independence and creating a more seamless dining experience.

To address these issues, all functionalities and services will be hosted on an online platform accessible from any 
device. This approach eliminates the need for specialized hardware, offering a more flexible and adaptable system. 
A local backup of the application will ensure functionality during internet outages, while relevant data will be 
automatically pushed to and stored in the cloud for reliability and accessibility.

## Objective Audience
This application is primarily targeted at the restaurant and bar industry, a sector that holds significant economic 
importance in Spain, particularly in the Community of Andalucía. With such a competitive market, even a slight edge 
in efficiency or customer satisfaction can determine the success or failure of a business.

Beyond seeking a competitive advantage, many bars and restaurants face high customer turnover and are constrained 
by the number of workers they can employ. By increasing worker efficiency and offloading certain tasks to clients, 
businesses can operate more smoothly, reduce wait times, and improve overall customer satisfaction.

## Market Analysis
The current market for restaurant terminal and ordering systems is saturated with applications that prioritize 
functionality over user experience. Many of these systems are clunky, difficult to navigate, and lack modern 
features that could streamline operations. Common features in existing applications include basic order management, 
payment processing, and inventory tracking. However, these systems often fail to integrate client-side 
functionalities or provide meaningful analytics for business improvement.

TaberNota aims to differentiate itself by offering a user-friendly interface for both workers and clients, seamless 
integration of client-side features (such as bill splitting and payment), and robust analytics for business 
optimization. By addressing the pain points of both workers and customers, TaberNota will provide a comprehensive 
solution that enhances operational efficiency and customer satisfaction.

## Key Functionalities
### 1. **Handle Ordering**
- Only servers should be able to place and manage orders.
- The application should streamline the ordering process, making it quick and intuitive for servers to input and 
modify orders.
- Different profiles (e.g., servers, managers, kitchen staff) should have tailored interactions and capabilities 
based on their roles.

### 2. **Allow Payment**
- The application should support payment processing for both servers and clients.
- Clients should be able to pay their bills directly through the app, with safeguards to prevent errors (e.g., QR 
codes on tables to link clients to their specific orders).
- Servers and managers should have full control over payment management, including applying discounts, voiding 
transactions, and processing refunds.

### 3. **Track Worker Hours**
- The application should automatically log the time each user (e.g., servers, managers) spends logged in.
- This data should be accessible to authorized roles for purposes such as payroll, performance analysis, and 
operational insights.

### 4. **Handle Inventory**
- The application should maintain an up-to-date inventory of items, editable by managers and servers.
- Features such as low-stock alerts and automatic reordering suggestions can help businesses manage their inventory 
more effectively.

### 5. **Allow and Provide Statistics**
- The application should generate detailed statistics on various aspects of the business, including:
    - Items sold (best-selling items, slow-moving items).
    - Worker activity (time logged in, orders processed).
    - Revenue generated per table or shift.
- These insights will help businesses identify trends, optimize operations, and make data-driven decisions.

### 6. **UI for Workers**
- The worker interface should be intuitive, easy to navigate, and adaptable to different restaurant layouts.
- Features such as customizable menus, quick-order shortcuts, and real-time updates will enhance usability.

### 7. **UI for Clients**
- The client interface should be simple and user-friendly, focusing on essential actions such as viewing menus, 
splitting bills, and making payments.
- The design should ensure that clients can only interact with their own table’s data, preventing errors or 
unauthorized access.

## Technologies to be Used
- **Programming Languages:** JavaScript (for front-end development) and Java (for back-end development).
- **Frameworks:** Vue.js (for building a responsive and dynamic front-end) and Spring Boot (for creating a robust 
and scalable back-end).
- **Libraries and Tools:**
    - Axios (for handling HTTP requests).
    - Bootstrap or Tailwind CSS (for styling and responsive design).
    - WebSocket (for real-time updates between the kitchen, servers, and clients).
    - Firebase or AWS (for cloud storage and data synchronization).
    - Local storage solutions (for offline functionality).
      
(Libraries and tools subject to change based on project requirements and team expertise.)

### Justification for Technology Choices
- **JavaScript and Vue.js:** These technologies were chosen for their flexibility, ease of use, and ability to 
create a responsive and interactive user interface. Vue.js, in particular, is lightweight and integrates well with 
other libraries, making it ideal for a dynamic application like TaberNota.
- **Java and Spring Boot:** Java is a reliable and widely-used language for back-end development, while Spring Boot 
simplifies the creation of scalable and secure applications. Together, they provide a solid foundation for handling complex business logic and data management.
- **Cloud and Local Storage:** Using cloud services like Firebase or AWS ensures data reliability and 
accessibility, while local storage solutions guarantee functionality during internet outages.

By leveraging these technologies, TaberNota will deliver a modern, efficient, and user-friendly solution that 
addresses the needs of both restaurant workers and clients, setting a new standard in the industry.  