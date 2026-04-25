# E-WareHouse_System
> A robust web-based solution for digitizing and automating warehouse operations.
 ### 1. Project Statement 
The E-Warehouse System fixes the problems found in old-fashioned warehouse management, where people often use paper lists or basic software that cannot keep track of exactly where items are stored. Instead of just knowing a product is in a building, this system uses a clear three-step organization—Warehouses, Zones, and Bins—to help workers find the right shelf in seconds. It also stops common data mistakes by using smart database rules that ensure every stock update is recorded correctly and completely. By adding automatic alerts for low stock and secure controls over who can change data, the system turns a messy storage room into a highly accurate, safe, and easy-to-manage digital workspace.

Therefore, there is a need for a modern, web-based solution that can streamline warehouse operations, improve accuracy, and provide real-time access to critical information.

---
### 2. Project Objectives
The objectives are divided into functional and technical goals:

   **𝔉𝔲𝔫𝔠𝔱𝔦𝔬𝔫𝔞𝔩 𝔊𝔬𝔞𝔩𝔰** 

The primary aim is to solve real-world logistical challenges through these key features:

* ***Inventory Tracking:*** Implement a robust CRUD system to manage products, categories, and stock quantities across multiple bin locations.

* ***Automated Stock Alerts:*** Develop a notification system that flags items falling below a predefined "Minimum Reorder Level."

* ***Supplier & Order Management:*** Create modules to track incoming shipments from suppliers and outgoing orders to customers.

**𝔗𝔢𝔠𝔥𝔫𝔦𝔠𝔞𝔩 𝔊𝔬𝔞𝔩𝔰**

Demonstrating mastery over the ASP.NET Web Forms lifecycle and database connectivity:

* ***State Persistence:*** Utilize ViewState and Session objects to maintain data consistency.

* ***Dynamic Data Binding:*** Use GridView and Repeater controls for real-time reporting.

* ***Secure Access:*** Implement Role-Based Access Control (RBAC) to distinguish between Admin and Staff users.
---
 ### Key Features of E-Warehouse
 
 **1. Location Management**
 
* **Warehouse Management:** High-level tracking of multiple storage buildings.

* **Zone Partitioning:** Organizing warehouses into logical sections like "Aisles" or "Cold Storage".

* **Bin-Level Tracking:** Precise inventory placement using specific Bin IDs and capacity limits.

---

**2. Advanced Inventory Operations**

Our system uses Stored Procedures to ensure that every stock change is accurate and logged.

* **Stock Adjustments:** A specialized module to manually add or subtract stock with mandatory reason codes for auditing.

* **Real-Time Stock Status:** A centralized view of total quantities available across the entire organization.

* **Product Location Mapping:** Tracking exactly how many units of a specific product are in which Bin.

* **Movement History:** An automated ledger that records every transaction, who performed it, and when.
 
---

**3. Secure User & Permission Management**

You have a robust security layer that controls exactly what each staff member can do.

* **Role-Based Access Control:** Defining users as Admins or Staff.

* **Granular Action Permissions:** Checkbox-level control over who has the right to Insert, Update, or Delete records.

* **Warehouse Assignment:** Restricting staff members to only see and manage stock within their assigned warehouse.

* **Account Status Control:** The ability to instantly activate or deactivate user accounts.

---

**4. Monitoring & Alerts**

Our database is "active," meaning it watches the data for you.

* **Low Stock Triggers:** Automatically detect when inventory falls below a safe threshold.

* **Automated Alerting:** A dedicated notification system that flags items needing immediate restocking.

---

**5. Product & Category Organization**

* **Dynamic Search & Filtering:** Interfaces designed to find products, zones, or bins instantly by name or status.

* **Category Management:** Grouping products into logical types to simplify reporting and navigation.

---
### 3. Functional and Non-Functional Requirements

   **Functional Requirements**
***
| No.  | Requirement                                                                       |
| ---- | --------------------------------------------------------------------------------- |
| FR1  | The system shall allow users to register, login, and logout                       |
| FR2  | The system shall allow admin to manage users (add, update, delete)                |
| FR3  | The system shall allow users to add, update, and delete products                  |
| FR4  | The system shall display a list of available products and their details           |
| FR5  | The system shall track inventory levels automatically                             |
| FR6  | The system shall alert users when stock is low                                    |
| FR7  | The system shall allow users to create and manage orders                          |
| FR8  | The system shall allow users to update order status (pending, shipped, delivered) |
| FR9  | The system shall allow users to manage suppliers information                      |
| FR10 | The system shall generate inventory reports                                       |
| FR11 | The system shall generate order reports                                           |
| FR12 | The system shall provide search and filter functionality                          |

   **Non-Functional Requirements**
***
| No.  | Requirement                                                      |
| ---- | ---------------------------------------------------------------- |
| NFR1 | The system shall respond to user actions within 2–3 seconds      |
| NFR2 | The system shall ensure secure login and data protection         |
| NFR3 | The system shall be user-friendly and easy to use                |
| NFR4 | The system shall be available and reliable with minimal downtime |
| NFR5 | The system shall support multiple users simultaneously           |
| NFR6 | The system shall be scalable for future improvements             |
| NFR7 | The system shall be compatible with modern web browsers          |
| NFR8 | The system shall ensure data backup and recovery                 |

### 4. Use Case Diagram

<img width="595" height="716" alt="Use Case Diagram E-Warehouse" src="https://github.com/user-attachments/assets/3c712cc9-bd27-438b-87a6-c66956c483cc" />

### 5. Database Diagram 

<img width="534" height="610" alt="image" src="https://github.com/user-attachments/assets/185cb5ed-0f43-470d-b957-054fc34fb6d6" />

---

### Authors

| No. | Name                    | Role      |
| --- | ----------------------- | --------- |
| 1   | UWAMAHORO Christa       | Developer |
| 2   | INGABIRE Confiance      | Developer |
| 3   | NIYOMUFASHA Olive       | Developer |
| 4   | UMWIZERWA Natete Belyse | Developer |


---
© 2026 Adventist University of Central Africa. All rights reserved.
