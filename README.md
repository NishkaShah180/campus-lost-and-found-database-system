# Campus Lost & Found Database Management System

## Overview

A centralized **Lost & Found Database Management System** designed for educational institutions to efficiently manage lost and found items across the campus. The system replaces informal reporting methods with a structured relational database, enabling users to report, search, claim, and track lost or found items while allowing administrators to verify claims and manage the item lifecycle.

The project covers the complete database design process, from **Software Requirement Specification (SRS)** to **ER modeling, normalization, relational schema design, and SQL implementation**.

---

## Key Features

- Role-Based Access Control (Public Users, Staff, Administrators)
- Lost Item and Found Item Reporting
- Search and Filter Items by Category
- Claim Verification using Proof of Ownership
- Item Status Tracking (Lost, Found, Claimed, Returned, Donated, Disposed)
- User Management for Students, Faculty, Staff, and Visitors
- Category Management
- Audit Trail for Item Lifecycle
- Scalable Database Design for Future Web/Mobile Integration

---

## Database Design

- Complete Software Requirement Specification (SRS)
- ER Diagram and Entity Analysis
- Relational Schema Design
- Normalization up to **Third Normal Form (3NF)**
- Primary Key and Foreign Key Constraints
- SQL DDL Implementation
- CRUD Operations
- Data Integrity and Constraint Management

---

## Entity Relationship Diagram

> *(The ER Diagram is available inside the `diagrams` folder.)*

![ER Diagram](diagrams/ER_Diagram.jpg)

---

## System Architecture

```
Students / Faculty / Visitors
            │
            ▼
     Application Layer
            │
            ▼
 Lost & Found Relational Database
            │
            ▼
 Administrators & Security Staff
```

The relational database acts as the **single source of truth** for all lost and found records, ensuring accurate tracking of every item from reporting to final resolution.

---

## User Roles

### Public Users

- Register/Login
- Report Lost Items
- Report Found Items
- Search Lost & Found Records
- Submit Ownership Claims
- Update/Delete Their Own Reports

### Staff

- Verify Lost & Found Reports
- Manage Item Records
- Update Item Status
- Verify Ownership Claims

### Administrators

- Manage Users
- Manage Categories
- Approve/Reject Claims
- Track Item Lifecycle
- Generate Reports
- Dispose or Donate Unclaimed Items

---

## My Contribution

- Designed the complete Software Requirement Specification (SRS)
- Created the Entity Relationship Diagram (ERD)
- Designed the Relational Database Schema
- Performed Database Normalization up to **3NF**
- Implemented SQL DDL Statements with Constraints
- Wrote SQL Queries for CRUD Operations
- Designed Role-Based Access Control and Database Workflow
- Modeled Item Claim, Verification, and Disposition Processes

---

## Technologies Used

- PostgreSQL
- SQL
- Database Management System (DBMS)
- ER Modeling
- Relational Database Design
- Database Normalization (1NF, 2NF, 3NF)

---

## Repository Structure

```
📂 diagrams
    └── ER_Diagram.jpg

└── LostNFound_DBMS.pdf
```

---

## Future Enhancements

- Web-based Lost & Found Portal
- Mobile Application Integration
- Automated Item Matching
- Email and SMS Notifications
- Advanced Reporting and Analytics
- Secure Authentication and Role Management

---

## Author

**Nishka Shah**