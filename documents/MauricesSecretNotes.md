## **Core Functionalities**
- **Real-time Data Handling:** All data needs to be in real-time.
- **Role-Based Access Control:** Use user roles to define functionalities, with flexibility for exceptions.
- **Order Management:**
    - Orders should be divided into rounds in the UI.
    - Ensure changes do not overlap (e.g., display "Waiting, the table or order is currently being interacted with").
    - The **Back button** must be the quickest and easiest thing to use.
- **Table Management:**
    - Allow tables to be joined or split (evaluate feasibility).
    - Dynamically generate and assign QR codes for tables (feature should be toggleable).
    - Generate a visual table layout (similar to an illustration tool).
- **Customization & UI Efficiency:**
    - Ensure **customizability of the UI** (themes, layouts, etc.).
    - Use color and design elements to improve user speed and reactions.
    - Include preset UI layouts for different restaurant types.

---

## **Security & Authentication**
- **Online & Offline Verification:**
    - Handle online verification; if it fails, provide an offline option.
    - Check how **automatic login** could affect security.
- **Password Management:**
    - Find a way to dynamically generate passwords or default to a static secret password.
    - Password recovery and most security-related tasks should require **manager approval**.
- **User Accountability:** Keep track of user actions for accountability.
- **Worker Role Management:**
    - Creation of worker roles must require **manager approval**.
    - Consider allowing users to have certain functionalities outside their default role.

---

## **Payments & Transactions**
- **Payment Methods:**
    - Implement **card scanning** or **Google Pay** for customer payments.
- **Client Ordering System (Optional):**
    - Allow clients to order from mobile devices, with a security measure requiring a waiter to **open the table first**.

---

## **Database & Backend**
- **Database Requirements:**
    - Should support **multiple restaurants**.
- **Technology Considerations:**
    - **Question:** Are **Express and Spring Boot** interchangeable? Can they coexist? Which is better for this project?

---

## **System Optimization & Testing**
- **Performance & User Flow:**
    - Ensure **efficiency is fundamental** to the design.
    - Check how **page reloading works when a mobile phone locks/unlocks**.
- **Component Structure:**
    - Separate functionalities into **components or pages** for easier management.
- **Sprint Planning:**
    - The **last week of each sprint** should focus on **testing and polishing**.

---

## **Extra Features & Optional Additions**
- **Printing & Reports:**
    - **Printer integration** for order receipts (optional).
    - Ability to **print statistics** on restaurant performance (optional).
- **Visual & Data Enhancements:**
    - Ability to **add photos for menu items**.
    - Assign different colors to items (consider a **color generator**).  
