# 📘 Educational Organisation using ServiceNow
## 📄 Project Information

| Field | Details |
|------|---------|
| **Date** | 02/11/2025 |
| **Team ID** |NM2025TMID02666|
| **Project Name** | Educational organization using ServiceNow |

## 📌 Project Overview
This project is a custom **Educational Management System** built on the **ServiceNow** platform.  
Its primary goal is to eliminate slow and error-prone manual data handling by automating the core administrative operations of an educational institution.

The application offers a **centralized, reliable, and user-friendly** interface that manages the complete student lifecycle — from admission to academic performance monitoring.

---

## ✅ Key Features

### 🎓 Admission Management
- Visual **Process Flow** defining stages: *New → In Progress → Joined / Rejected*
- Auto-generate unique **Admin Number** (e.g., `SAL0000001`)
- Structured data model using **Table Inheritance** (Extends *Salesforce* base table)

### 🧠 Smart Form Automation
- **Pincode Auto-Fill:**
  - Automatically populates **City**, **Mandal**, and **District** when PIN code is entered
- **Progress Auto-Fill:**
  - Student details (Name, Father's Name, etc.) auto-populate when **Admission Number** is selected

### 📝 Automatic Grade Calculator
| Function | Trigger | Result |
|---------|---------|--------|
| Total Marks | Entering subject marks | Auto-calculated |
| Percentage | After calculating total | Auto-calculated |
| Result | Based on percentage rules | Pass / Fail set automatically |

✅ **All result fields are read-only** to maintain data accuracy and prevent errors.

---

## 🛠 Technology Stack

| Category | Tools/Features Used |
|---------|-------------------|
| Platform | ServiceNow |
| Data Model | Custom Tables + Table Inheritance |
| Logic Implementation | Client Scripts (`onLoad`, `onChange`) |
| APIs | GlideForm (`g_form`) |
| UI | Form Layout + Process Flow |
| Configurations | Number Maintenance, Update Sets |

---

## 🚀 Application Scope
This solution improves:
✔ Student data accuracy  
✔ Operational efficiency  
✔ Transparency in admission and academic processes  

Perfect for **schools, colleges, and training centers** seeking workflow automation.

---

## 📦 Import & Setup (Will be Added)
✅ Update Set installation instructions  
✅ Navigation guide  
✅ Screenshots and demo workflow  

---

## 🔗 Future Enhancements
- Parent & Student Portal
- Attendance Tracking Module
- Email & SMS Notifications
- Role-Based Access Control
- Analytics Dashboard (Performance Insights)


---

⭐ *If you like this project, feel free to contribute or share your feedback!*
