# IDEMI Animation Department — Task & Repository Database

[![GitHub Pages](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-success?style=for-the-badge&logo=github)](https://hawkzen001.github.io/idemi-task-management-app/)
[![Database](https://img.shields.io/badge/Database-Google%20Cloud%20Firestore-orange?style=for-the-badge&logo=firebase)](https://console.firebase.google.com/project/idemi-task-management-db/overview)
[![Region](https://img.shields.io/badge/Region-asia--south1%20(Mumbai)-blue?style=for-the-badge&logo=googlecloud)](https://cloud.google.com/about/locations/mumbai)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)

> **Live Application URL**: [https://hawkzen001.github.io/idemi-task-management-app/](https://hawkzen001.github.io/idemi-task-management-app/)

---

## 📌 Overview

The **IDEMI Task & Repository Database** is a centralized, high-performance web application built specifically for the **Animation Department at IDEMI (Institute for Design of Electrical Measuring Instruments), Mumbai**.

The application is powered by a dedicated **Google Cloud Firestore Database** (`idemi-task-management-db`) hosted in the `asia-south1` (Mumbai) region. It provides instant real-time synchronization across all devices and browsers without requiring personal access tokens or external spreadsheet permissions.

---

## 🚀 Key Features

### 1. ⚡ Real-Time Google Cloud Firestore Database
- **Dedicated Cloud Database**: Project `idemi-task-management-db` hosted in `asia-south1` (Mumbai).
- **Sub-Second Real-Time Synchronization**: Built-in WebSockets and `onSnapshot` listeners push modifications, additions, and deletions immediately to every connected device without page refreshes.
- **Zero Token Friction**: No personal access tokens (PAT) or login credentials needed by team members.
- **Offline Persistence & Conflict Resolution**: Automatic local caching and background syncing when connection recovers.
- **Database Settings & Diagnostics**: In-app modal for live connection testing, collection record counts, and full backup/restore.

### 2. 📋 Dual-Dataset Architecture
- **Active Tasks (21 tasks)**: Real-time departmental tasks spanning Design, Advertising, Web Development, Audits, and Training.
- **Completed Archive (102 tasks)**: Historical record of finalized tasks, semester exams, student certifications, and tender documentation.
- **All Records (123 items)**: Unified view across all active and completed records.

### 3. 📊 Multi-View Layouts & Zero-Scroll Horizontal Fit
- **Task Database Table View**: Clean, compact table displaying all 14 columns simultaneously across full screen width without horizontal scrolling. Includes sticky action column and quick inline status changes.
- **Interactive Kanban Board**: Visual columns organized by progress state (*Not Started, In Progress, Delayed, On Hold, Completed*) with quick-action status transition buttons.
- **Team Workload & Analytics**: Workload distribution metrics and status summaries grouped by assignee (Nilesh Sharma, Aayush Raisoni, Shaunak Kolte, Abhishek Kamble, Sushil Baviskar, Vishal Angre, etc.).
- **Department Repository Master View**: Directory of 34 official IDEMI links, documentation portals, and external resources with category badges, description, and direct launch links.

### 4. 🗹 Select All & Bulk Deletion
- Bulk selection checkboxes across individual rows or the entire visible dataset.
- Real-time selection counter badge in action bar.
- One-click **Delete Selected** with batch Firestore deletion and instant UI update.

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
- **Database**: Google Cloud Firestore (Native Mode, `asia-south1`).
- **Real-Time Client**: Firebase JavaScript SDK v10 (Compat Mode).
- **Static Baseline**: `data/database.json` (seeded with 21 active tasks, 102 completed tasks, 34 links).
- **Hosting**: Hosted serverlessly on **GitHub Pages**.

---

## 📁 Repository Structure

```text
├── data/
│   └── database.json                    # Baseline departmental database file
├── firebase.json                        # Firebase configuration
├── firestore.rules                      # Cloud Firestore security rules
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
