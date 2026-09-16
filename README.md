# 🎓 Smart Campus Issue Management System

A role-based university issue management platform designed to simplify campus complaint reporting, tracking, assignment, and resolution.

The system provides a centralized platform where students can report campus-related issues, staff can manage assigned issues, and administrators can monitor the overall issue-resolution process.

---

## 🚀 Project Overview

The **Smart Campus Issue Management System** is a full-stack web application developed to improve the way university issues and complaints are reported and managed.

Traditional complaint systems often depend on manual reporting, making it difficult to track the status of an issue, assign it to the appropriate staff member, and monitor resolution time.

This project provides a centralized digital platform for managing the complete issue lifecycle.

### 🎯 Main Objectives

- Allow students to report campus issues easily
- Provide issue tracking and status updates
- Assign issues to appropriate maintenance staff
- Provide role-based access
- Help administrators monitor reported issues
- Maintain a structured issue management workflow
- Provide a scalable architecture for future database integration

---

## ✨ Features

### 🔐 Authentication

- Student/Reporter registration
- Login interface
- Authentication API foundation
- Role-based access architecture

### 📝 Issue Management

- Report campus-related issues
- Categorize issues
- Track issue status
- View issue details
- Monitor issue progress

### 👨‍🎓 Student / Reporter

Students can:

- Create an issue
- View submitted issues
- Track issue status
- View issue details
- Monitor resolution progress

### 🧑‍🔧 Maintenance Staff

Staff can:

- View assigned issues
- Update issue status
- Manage ongoing issues
- Mark issues as resolved

### 👨‍💼 Administrator

Administrators can:

- Monitor campus issues
- Manage users
- Assign issues to staff
- Monitor issue status
- View management statistics

## 🔄 Issue Management Workflow
Student Reports Issue
          │
          ▼
     Issue Created
          │
          ▼
   Admin Reviews Issue
          │
          ▼
   Assign Staff Member
          │
          ▼
    Staff Works on Issue
          │
          ▼
    Update Issue Status
          │
          ▼
       Issue Resolved
          │
          ▼
     Student Notified
     
## 🛠️ Technology Stack

Frontend:

-React.js
-JavaScript
-Tailwind CSS
-HTML5
-CSS3

Backend:

-Node.js
-Express.js
-REST API

Development:

-Git
-GitHub
-VS Code
-npm

Deployment:

-Netlify – Frontend
-Render – Backend
-Future Database

The architecture is prepared for database integration such as:

MongoDB
---

## 🏗️ System Architecture

```text
                  SMART CAMPUS ISSUE MANAGEMENT
                              │
                              ▼
                    ┌───────────────────┐
                    │     FRONTEND      │
                    │ React + Tailwind  │
                    └─────────┬─────────┘
                              │
                         REST API
                              │
                              ▼
                    ┌───────────────────┐
                    │      BACKEND      │
                    │ Node.js + Express │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │   AUTHENTICATION  │
                    │   & API SERVICES  │
                    └─────────┬─────────┘
                              │
                              ▼
                    ┌───────────────────┐
                    │      DATABASE     │
                    │ Future Integration│
                    └───────────────────┘

PostgreSQL
MySQL
