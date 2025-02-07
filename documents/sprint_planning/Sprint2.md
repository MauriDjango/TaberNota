# Sprint 2 - Core Functionalities & Real-Time Updates

## Backend (Spring Boot & Database)
- [ ] Implement **real-time updates** using WebSockets or an alternative solution.
- [ ] Develop **order management system** (create, update, cancel orders).
- [ ] Implement **checks and balances** to prevent conflicting changes (e.g., "Waiting, the table or order is currently being interacted with.").
- [ ] Develop **role management system** (creation of worker roles requires manager approval).
- [ ] Implement **dynamic password generation** for new worker accounts or fallback to a static secret password.
- [ ] Research and integrate **offline mode handling** (e.g., storing changes locally until reconnected).
- [ ] Implement **basic payment handling** system (Google Pay, card scanning research).
- [ ] Ensure proper **audit logging** to track user actions for accountability.

## Frontend (Vue.js & UI/UX)
- [ ] Implement **real-time UI updates** for table interactions and order changes.
- [ ] Develop **UI for order visualization**, ensuring orders are divided into rounds.
- [ ] Add ability to **assign different colors to menu items** (consider a color generator).
- [ ] Implement **QR code scanning for table access** (enable/disable as needed).
- [ ] Allow **customization of the UI interface** based on restaurant preferences.
- [ ] Ensure **separate functionalities are properly managed in components**.

## Design (UI/UX Considerations)
- [ ] Improve **table layout UI** (Illustrator-like graphics for table placement).
- [ ] Ensure tables can be **joined or split** dynamically.
- [ ] Implement **Back button usability improvements** to enhance workflow efficiency.
- [ ] Research **UX enhancements** to improve worker speed (e.g., color coding, shortcut keys).
- [ ] Plan **printable statistics feature** (optional).
- [ ] Start designing **preset UI layouts** for different restaurant types.

## Setup & Testing
- [ ] Test **real-time updates** for consistency and performance.
- [ ] Check how **automatic login security risks** can be mitigated.
- [ ] Test **offline mode** to ensure proper data syncing when reconnected.
- [ ] Verify **database scalability** for handling multiple restaurants.

## Sprint 2 Deliverables:
✔️ **Backend:** Real-time updates, order management, worker role system.  
✔️ **Frontend:** Real-time UI updates, order visualization, QR code handling.  
✔️ **Design:** Improved table layout UI, usability enhancements.  
✔️ **Setup & Testing:** Real-time update validation, offline mode testing, security checks.
