# Agent Performance Counter & Admin Dashboard

A comprehensive web application designed for call center agents to track their daily performance metrics, and for administrators to manage teams, view analytics, and broadcast announcements.

## Features

### 👨‍💻 Agent View
* **Daily Counter:** Track calls, payments, full payments, and accounts removed from collections.
* **Auto-Calculations:** Automatically calculates conversion percentages and estimated time available.
* **Tier System:** Visual badges (Tier 1-5) based on performance thresholds.
* **Real-Time Chat:** Direct messaging with supervisors and admins.
* **Announcements:** Sticky pinned banners for important global or team-specific updates.

### 👑 Admin Dashboard
* **User Management:** Create, edit, deactivate, and delete Agent and Supervisor accounts.
* **Kanban Team Organization:** Drag-and-drop interface to assign agents to specific supervisors.
* **Performance Analytics:** View aggregated stats for the entire floor, specific teams, or individual agents.
* **Hierarchical Announcements:** Broadcast pinned messages globally, to specific teams, or to individual agents.
* **Export:** Export raw call logs or aggregated performance reports directly to Excel (.xlsx).

## Tech Stack
* **Frontend:** HTML5, CSS3, Vanilla JavaScript
* **Data Storage:** LocalStorage (JSON)
* **Libraries:** Chart.js (Analytics), SheetJS (Excel Export)

## How to Run
1. Clone or download the repository.
2. Open `index.html` in any modern web browser.
3. **Default Admin Login:**
   * **Email:** admin@admin.com
   * **Password:** admin
