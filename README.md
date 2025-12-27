# 🛠️ GearGuard — The Ultimate Maintenance Tracker

GearGuard is a web-based **Maintenance Management System** that helps organizations track their equipment, manage maintenance teams, and automate repair workflows.  
It provides a smart, professional, and Odoo-like solution for handling company assets and maintenance operations.

---

## 📌 Project Objective

To build a complete maintenance management platform that connects:

- **Equipment** → What needs repair  
- **Maintenance Teams** → Who performs the repair  
- **Maintenance Requests** → The work to be done  

and automates the entire maintenance lifecycle from issue reporting to job completion.

---

## 👥 User Roles

| Role | Responsibilities |
|-----|----------------|
**Admin / Manager** | Manage equipment, teams, technicians, scheduling |
**Employee (User)** | Report equipment issues |
**Technician** | Perform repairs & update request status |

---

## 🧱 Core Modules

### 1. Equipment Module

Stores complete details of company assets.

**Fields**
- Equipment Name & Serial Number  
- Department & Assigned Employee  
- Physical Location  
- Purchase Date & Warranty Expiry  
- Assigned Maintenance Team  
- Default Technician  

**Features**
- Search & filter by department or employee  
- Smart **Maintenance Button** showing open request count

---

### 2. Maintenance Team Module

- Create specialized teams (IT, Mechanics, Electricians, etc.)
- Assign technicians to teams
- Enforces team-based request handling

---

### 3. Maintenance Request Module

Manages the full lifecycle of maintenance work.

**Request Types**
- Corrective (Breakdown)
- Preventive (Routine Maintenance)

**Workflow Stages**

