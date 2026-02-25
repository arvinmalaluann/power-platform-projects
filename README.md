# Digital Authorization and e-ID Management System (DAeMS)

> A centralized digital ID lifecycle management system built using Microsoft Power Apps (Canvas App).

---

## 📌 Overview

The **Digital Authorization and e-ID Management System (DAeMS)** is a Power Apps Canvas application developed to digitalize the complete employee ID lifecycle — from creation and authorization assignment to digital preview and soft-copy generation.

The system is designed for licensed users within JGSOC and ensures secure, role-based access to employee ID records and authorization data.

---

## 🎯 Purpose

DAeMS aims to:

- Replace manual ID processing
- Centralize authorization management
- Provide digital ID previews
- Enable soft-copy ID requests
- Support administrative mass export of digital IDs
- Automate notifications via email

---

## 👥 Target Users

- Licensed Users (JGSOC)
- HR / Admin Personnel
- Safety & Authorization Officers
- General Users (limited access)

---

## 🏗 Application Architecture

**App Type:** Canvas App  
**Platform:** Microsoft Power Apps  
**Data Source:** SharePoint Lists  
**Automation:** Power Automate  
**Notification Integration:** Outlook  

---

## 🔐 Security Model

### Role-Based Access Control (RBAC)

| Role | Permissions |
|------|------------|
| Admin | Full CRUD, Mass Export, User Management |
| Licensed User | Read & Update Own Profile |
| Common User | View Own ID, Request Soft Copy |

---

## ✨ Key Features

### 🆔 ID Lifecycle Management
- ID creation and updating
- Authorization assignment
- Digital front and back ID preview
- QR code generation

### 👤 Employee Management
- Create, Read, Update, Delete (Admin)
- Employee search and filtering
- Department and manager mapping

### 📄 Soft Copy Generation
- Individual soft copy request (self only)
- Admin mass export of digital IDs
- PDF generation via Power Automate

### 🔔 Notifications
- Automated email notifications via Outlook
- Trigger-based workflows using Power Automate

---

## 🔄 System Workflow

1. Admin creates or updates employee record
2. Authorizations are assigned
3. ID is dynamically generated
4. User may request soft copy (self only)
5. Admin may perform bulk export
6. Email notifications are triggered (if configured)

---

## 📊 Data Model (High-Level)

SharePoint Lists Used:

- Employees
- Authorizations
- Roles
- Departments
- ID Requests

---

## 🚀 Deployment

Currently deployed via **Direct Publish** in Power Apps within a single organizational environment.

### Deployment Approach

**Direct Publish**
- App is built and published in one environment
- Shared directly with licensed users
- Suitable for UAT and controlled environments

Future enhancement may include:
- Packaging inside a Power Platform Solution
- Managed Solution export for production deployment

---

## 📋 Environment Requirements

- Microsoft 365 Account
- Power Apps License
- SharePoint Access
- Outlook Access (for notifications)

No premium connectors required.

---

## 📌 Project Status

🟡 Under User Acceptance Testing (UAT)

---

## 🔮 Roadmap

- QR Code Scanner Integration
- Audit Logging
- ID Expiration Notifications
- Workflow Approval Enhancements
- Analytics Dashboard
- Mobile Optimization Improvements

---

## 📄 License

Internal Organizational Project  
Not intended for public distribution.

---

## 👨‍💻 Maintainer

Developed for JGSOC  
Power Platform – Canvas App Solution
