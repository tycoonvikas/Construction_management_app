# 🏗️ SiteMaster AI - Construction Management Platform

A comprehensive, AI-enhanced web application designed to streamline construction site management. It bridges the gap between on-site workers and project managers by providing real-time progress tracking, financial oversight, and automated AI reporting.

## ✨ Key Features

### 👨‍💼 Admin Portal (Project Manager)
* **Global Dashboard:** High-level overview of all active projects, budget health, and task completion rates.
* **Project & Task Management:** Create projects, set budgets, assign tasks to specific workers, and monitor deadlines.
* **Real-Time Live Feed:** View daily site logs, photos, and updates submitted by workers on the ground.
* **Finance Tracking:** Track material purchases and labor costs against the total project budget (Inspired by DhanSafar).

### 👷‍♂️ Worker Portal (Site Supervisor/Contractor)
* **Mobile-First Interface:** Optimized for quick, on-the-go data entry from the construction site.
* **Daily Site Logs:** Easy submission of completed work, material consumption, and site photos.
* **Task Dashboard:** A prioritized list of daily assigned tasks.
* **Attendance Tracking:** Simple Clock-In / Clock-Out functionality.

### 🤖 AI Integrations (Powered by Google Gemini)
* **Smart Receipt Scanning:** Automatically extracts material names and total costs from uploaded receipt images to update the finance tracker.
* **Automated Daily Briefings:** AI compiles scattered worker logs into a clean, executive summary for the Admin every evening.
* **Risk Prediction:** Highlights potential schedule delays and budget overruns based on current project velocity.

---

## 🛠️ Tech Stack

* **Frontend:** Next.js, React, Tailwind CSS, Shadcn UI
* **Backend:** Next.js API Routes / Node.js
* **Database:** PostgreSQL (via Prisma ORM / Supabase)
* **AI:** Google Gemini API 

---

## 🚀 Getting Started

### Prerequisites
Make sure you have Node.js and npm (or pnpm/yarn) installed on your machine.

### Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/sitemaster-ai.git](https://github.com/yourusername/sitemaster-ai.git)
   cd sitemaster-ai
