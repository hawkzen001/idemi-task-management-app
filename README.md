# IDEMI Animation Department — Task & Repository Database

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-success?style=for-the-badge&logo=github)](https://hawkzen001.github.io/idemi-task-management-app/)
[![Autonomous Database](https://img.shields.io/badge/Database-GitHub%20Repo%20JSON-blue?style=for-the-badge&logo=json)](data/database.json)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

> **Live Application URL**: [https://hawkzen001.github.io/idemi-task-management-app/](https://hawkzen001.github.io/idemi-task-management-app/)

---

## 📌 Overview

The **IDEMI Task & Repository Database** is a centralized, high-performance web application built specifically for the **Animation Department at IDEMI (Institute for Design of Electrical Measuring Instruments), Mumbai**.

The application operates on its own **autonomous repository database** (`data/database.json`), completely decoupled and independent of any external Google Sheet. All departmental records, progress states, and repositories are managed directly inside this GitHub repository.

---

## 🚀 Key Features

### 1. 🗄️ Autonomous GitHub Repository Database
- **Committed Source of Truth**: All tasks, completed archives, categories, and department repositories are stored directly in `data/database.json`.
- **Decoupled from Google Sheets**: Zero reliance on external spreadsheet connections or third-party sheet permissions.
- **Direct GitHub REST API Sync**: Commit changes, new tasks, and status updates directly back to GitHub repository `data/database.json` via official GitHub API (`PUT /contents/data/database.json`).
- **Database Settings & Security**: Manage GitHub Personal Access Token (PAT) securely inside browser localStorage with connection and write permission testing.
- **One-Click Backup & Restore**: Export full database snapshots as `.json` files or restore previous versions on demand.

### 2. 📋 Dual-Dataset Support
- **Active Tasks (21 tasks)**: Real-time departmental tasks spanning Design, Advertising, Web Development, Audits, and Training.
- **Completed Archive (102 tasks)**: Historical record of finalized tasks, semester exams, student certifications, and tender documentation.
- **All Records (123 items)**: Unified view across all active and completed records.

### 3. 📊 Multi-View Layouts & Zero-Scroll Horizontal Fit
- **Task Database Table View**: Clean, compact table displaying all 14 columns simultaneously across full screen width without horizontal scrolling. Includes sticky action column and quick inline status changes.
- **Interactive Kanban Board**: Visual columns organized by progress state (*Not Started, In Progress, Delayed, On Hold, Completed*) with quick-action status transition buttons.
- **Team Workload & Analytics**: Workload distribution metrics and status summaries grouped by assignee (Nilesh Sharma, Aayush Raisoni, Shaunak Kolte, Abhishek Kamble, Sushil Baviskar, Vishal Angre, etc.).
- **Department Repository Master View**: Directory of official IDEMI links, documentation portals, and external resources with category badges, description, and direct launch links.

### 4. 🗹 Select All & Bulk Deletion
- Bulk selection checkboxes across individual rows or the entire visible dataset.
- Real-time selection counter badge in action bar.
- One-click **Delete Selected** with instant state re-calculation and database update.

### 5. 🔍 Smart Search & Multi-Criteria Filtering
- Real-time search across Task IDs (e.g., `T001`, `T038`), Titles, Descriptions, Assignees, and Dependencies.
- Dropdown filters for **Progress Status**, **Priority Level** (*High, Medium, Low*), **Category**, and **Assignee**.
- One-click **Clear Filters** shortcut.

### 6. ✍️ Full Task Lifecycle Management (CRUD)
- Create new tasks with automated Task ID suggestion.
- In-place editing of title, description, category, assignee, priority, start/due/completion dates, dependencies, comments, and links.
- Automatic completion date stamping when marking progress as *Completed*.

---

## 🛠️ Tech Stack

- **Core**: Vanilla HTML5, CSS3, and JavaScript (ES6+).
- **Database**: Repository JSON database (`data/database.json`) synced via GitHub REST API v3.
- **Styling**: Modern design system using CSS custom properties, responsive grid/flexbox, and streamlined horizontal fit.
- **Hosting**: Hosted serverlessly on **GitHub Pages**.

---

## 📁 Repository Structure

```text
├── data/
│   └── database.json                    # Autonomous departmental database file
├── index.html                           # Main entry point for GitHub Pages
├── idemi_task_management_app.html       # Standalone single-page web app source
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
