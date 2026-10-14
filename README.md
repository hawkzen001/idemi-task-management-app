# IDEMI Animation Department — Task & Repository Management App

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-success?style=for-the-badge&logo=github)](https://hawkzen001.github.io/idemi-task-management-app/)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

> **Live Application URL**: [https://hawkzen001.github.io/idemi-task-management-app/](https://hawkzen001.github.io/idemi-task-management-app/)

---

## 📌 Overview

The **IDEMI Task & Repository Management App** is a centralized, high-performance web dashboard built specifically for the **Animation Department at IDEMI (Institute for Design of Electrical Measuring Instruments), Mumbai**.

It provides an intuitive interface to manage, visualize, and track departmental tasks, student admissions, curriculum development, marketing campaigns, infrastructure, and institutional repositories directly derived from the official live Google Sheet.

---

## 🚀 Key Features

### 1. 📋 Dual-Dataset Support
- **Active Task Sheet (21 tasks)**: Real-time departmental tasks spanning Design, Advertising, Web Development, Audits, and Training.
- **Completed Work Archive (102 tasks)**: Historical record of finalized tasks, semester exams, student certifications, and tender documentation.
- **Combined View (123 items)**: Unified view across all active and completed records.

### 2. 📊 Multi-View Layouts
- **Task Sheet Table View**: Full-featured tabular overview with status pill indicators, priority badges, dates, assignees, and direct external action links.
- **Interactive Kanban Board**: Visual columns organized by progress state (*Not Started, In Progress, Delayed, On Hold, Completed*) with quick-action status transition buttons.
- **Team Workload & Analytics**: Workload distribution metrics and status summaries grouped by assignee (Nilesh Sharma, Aayush Raisoni, Shaunak Kolte, Abhishek Kamble, Sushil Baviskar, Vishal Angre, etc.).
- **Department Repository Master View**: Directory of official IDEMI Google Sheets, Portals, and external resources with category badges, description, and direct launch links.

### 3. 🔍 Smart Search & Multi-Criteria Filtering
- Real-time search across Task IDs (e.g., `T001`, `T038`), Titles, Descriptions, Assignees, and Dependencies.
- Dropdown filters for **Progress Status**, **Priority Level** (*High, Medium, Low*), **Category**, and **Assignee**.
- One-click **Clear Filters** shortcut.

### 4. ✍️ Full Task Lifecycle Management (CRUD)
- Create new tasks with automated Task ID suggestion.
- In-place editing of title, description, category, assignee, priority, start/due/completion dates, dependencies, comments, and links.
- Delete or archive tasks with instant recalculation of metrics.
- Automatic completion date stamping when marking progress as *Completed*.

### 5. 💾 Export, Import & Offline Persistence
- **CSV Export**: Export filtered or complete datasets to standard CSV files.
- **CSV Import**: Ingest updated rows directly from spreadsheet exports into the app.
- **LocalStorage Sync**: Edits, additions, and updates are automatically persisted in browser storage.
- **Reset to Defaults**: One-click reset to restore the original baseline data.

---

## 🛠️ Tech Stack

- **Core**: Vanilla HTML5, CSS3, and JavaScript (ES6+).
- **Styling**: Modern design system using CSS custom properties (variables), clean typography, flexbox/CSS grid, and glassmorphic header cues.
- **Deployment**: Zero-dependency static build hosted on **GitHub Pages**.

---

## 📁 Repository Structure

```text
├── index.html                           # Main entry point for GitHub Pages
├── idemi_task_management_app.html       # Standalone single-page web app source
├── Task & Repository Sheet - ANI...url  # Desktop shortcut to the Live Google Sheet
└── README.md                            # Comprehensive project documentation
```

---

## 🌐 Live Access

Access the live web application on any device (Desktop, Tablet, Mobile) at:
**[https://hawkzen001.github.io/idemi-task-management-app/](https://hawkzen001.github.io/idemi-task-management-app/)**

---

## 👤 Author & Department

- **Department**: Animation Department, IDEMI Mumbai
- **Maintainer**: Nilesh Sharma ([hawkzen001](https://github.com/hawkzen001))
- **Live Google Sheet**: [Animation Department Task & Repository Sheet](https://docs.google.com/spreadsheets/d/1sXfyIN1z0r46S8cdKIB9U3ED05x1n8O7cJWYpGZVAMA/edit?usp=sharing)
