#  Apple Inventory System  
### Enterprise Inventory & Order Management System  
Built with Oracle APEX & Oracle Database

---

## 📌 Project Overview

Apple Inventory System is a full-featured enterprise-style web application developed using **Oracle APEX** and **Oracle Database**.

The system simulates a real-world inventory and sales management platform where administrators can manage products, customers, and multi-step sales orders within a structured relational database environment.

This project demonstrates practical implementation of:

- Relational Database Design
- SQL & PL/SQL Programming
- Oracle APEX Page Development
- Business Logic Handling (APEX Processes)
- Interactive Reports & Data Visualization
- REST API Integration
- Wizard-Based Workflow Implementation

---

##  Tech Stack

| Layer | Technology |
|-------|------------|
| Database | Oracle Database |
| Backend Logic | PL/SQL |
| Application Framework | Oracle APEX |
| UI Components | Interactive Reports, Forms, Charts, Cards |
| Integration | REST API (Exchange Rates) |

---


##  Core Features

###  Dashboard
- System overview metrics
- Orders & products statistics
- Quick navigation

###  Product Management
- Interactive Products Report
- Product Form (CRUD operations)
- Product image management
- Products by category view
- Real-time stock tracking

###  Category Management
- Categories report
- Add / Edit categories

###  Customer Management
- Customers report
- Customer form (Create / Update / Delete)

###  Order Management (Wizard-Based Flow)

Multi-step enterprise order processing:

1. Choose Customer  
2. Add Items (Cart logic using collection/session handling)  
3. Review & Confirm  
4. Finish & Update Order Status  

Additional order features:
- Order details page
- Change order status
- Status filtering
- Date range filtering

###  Analytics & Reporting
- Inventory valuation
- Order analysis
- Category-based insights
- Dynamic filtering reports

###  Exchange Rate Integration
- REST API consumption
- External currency rate retrieval

###  Security & Administration
- Login page
- Admin users management
- Internal admin notes system

---

## 🗄️ Database Architecture

The system is built using a fully normalized relational schema with strict constraints and enforced relationships.

### Main Tables

- **Categories**
- **Products**
- **Customers**
- **Orders**
- **Order_Items**
- **Admin_Users**
- **Admin_Notes**

### Key Relationships

- One Category → Many Products  
- One Customer → Many Orders  
- One Order → Many Order Items  
- One Product → Many Order Items  

All relationships are enforced using **Foreign Key Constraints**.

✔ Identity columns  
✔ Check constraints  
✔ Unique constraints  
✔ No database triggers (Business logic handled inside APEX)

---

##  System Architecture

###  Database Layer
- Relational schema
- Data integrity enforcement
- Seed data

###  Application Logic Layer
- APEX Processes
- PL/SQL blocks
- Dynamic Actions
- Session state management
- Wizard flow control

###  Presentation Layer
- Interactive Reports
- Forms
- Wizard Pages
- Charts
- Cards
- Filters

---

##  Repository Structure

| File | Description |
|------|------------|
| `database_Schema.sql` | Database schema + constraints + seed data |
| `application_export.sql` | Full Oracle APEX application export |
| `README.md` | Project documentation |

---

##  How to Run

1. Import `database_Schema.sql` into an Oracle Database schema.
2. Import `application_export.sql` into Oracle APEX.
3. Run the application from APEX App Builder.

---

## 🎓 Academic Context

This project was developed as part of an advanced Database Systems and Oracle APEX academic course.

It demonstrates:

- Enterprise database design principles
- Business logic implementation without triggers
- Structured application architecture
- Multi-step transactional workflows
- Real-world database application development

---

##  Author

Developed by: **Lyana Mansour Abu Baker**  , **Omar Yousif Al-Hamdan** 
Oracle APEX & Database Systems Project
