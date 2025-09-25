# Project & Task Management

This document defines how SETTribe teams will manage tasks, track progress, and report status using **GitHub Projects (Kanban)**.

---

## 🔹 1. Project Setup
- **Project Type:** Kanban  
- **Linked Repository:** Only **Dev repo** (all development activities happen here).  
- **Custom Fields:**  
  - Deleted unused fields → *priority, estimate, etc.*  
  - Added new field → **Man hrs** (developer effort estimate).  
- **Ideal Project Template for Copy Purpose:**  
  👉 [SETTribe Dev Project Template](https://github.com/orgs/SETTribe-IT-Solutions/projects/1)  

👉 **Best Practice:** Always **create project directly from repo** so issues link automatically.  

---

## 🔹 2. Task Creation Rules

### 2.1 Title Convention (Prefix Placeholders)
Use prefixes to quickly identify task type:

- **[DB]** → Database tasks  
- **[FE]** → Frontend tasks  
- **[BE]** → Backend tasks  
- **[Test]** → Testing/QA tasks  
- **[Bug]** → Bug/defect tasks  
- **[Suggestion]** → Ideas/improvements  
- **[Feature]** → Full feature requiring FE + BE + DB
- **[Training]** → Project Training for client
- **[Reminder]** → Follow-up or scheduled reminder tasks
- **[Purchase]** → Payments, procurement, or subscription tasks
- **[Video]** → Video creation/editing tasks
- **[PPT]** → Presentation or user manual preparation tasks

✅ **Examples**:  
- `[FE] Create Login Page`  
- `[BE] Add DB Connection`  
- `[Test] Test Login Functionality`  
- `[Bug] Login page is not working as expected`  
- `[Feature] Implement User Authentication`
- `[Training] Conduct Git Workflow Training Session`
- `[Reminder] Follow up with client on project feedback (Friday 3 PM)`
- `[Purchase] Renew SSL Certificate for domain`
- `[Video] Create demo video for survey reporting tool`
- `[PPT] Prepare project presentation for stakeholder meeting`

---

### 2.2 Labels
Each task must have **2 types of labels**:

- **Task Label** (what type of work) → UI/UX, BE, Test, Bug, Suggestion, Feature, Training, Remainder, Purchase, Video, PPT  
- **Priority Label** (importance level):  
  - **P0** → Critical / must fix immediately  
  - **P1** → High priority  
  - **P2** → Medium  
  - **P3** → Low  

✅ **Example:**  
`[BE] Add DB Connection` → Labels: **BE, P1**

---

### 2.3 Mandatory Fields to Fill in Every Task
When creating an issue/task, always add:  
- ✅ Title with prefix  
- ✅ Labels (task type + priority)  
- ✅ Start Date, Due Date & Man hrs (effort estimate)  
- ✅ Assignee (responsible person)  
- ✅ Milestone (sprint/release)  

---

## 🔹 3. Milestones (Sprints/Releases)

Milestones are used to track sprints or releases.  

**Naming convention:**  
- `Sprint-1 (Sept 01–15, 2025)`  
- `Sprint-2 (Sept 16–30, 2025)`  
- `Sprint-3 (Oct 01–15, 2025)`  

👉 **How to Create:**  
`Repo → Issues → Milestones → New milestone`  

👉 **Best Practice:**  
- Add description of planned features.  
- Close milestone when sprint ends.  

---

## 🔹 4. Reports & Insights for Leadership
Using **Kanban + labels + milestones**, we can generate:  

- 📊 **Burndown Chart** → via Milestones (issues closed vs. remaining).  
- ⏱ **Effort Tracking** → Sum of *Man hrs* across tasks.  
- 👩‍💻 **Resource Utilization** → Tasks per assignee with Man hrs.  
- 🚨 **Delayed Tasks** → Issues past due date.  
- 📦 **Feature Progress** → Tasks grouped by Feature milestone.  

---

## 🔹 5. Notes & Best Practices
- ❌ Don’t use GitHub’s **Issue Type** dropdown → manage everything via **labels**.  
- ✅ Always link tasks to **repo + project + milestone** for visibility.  
- ✅ Keep tasks **small & actionable** (1–2 days effort).  
- ✅ Use **comments inside issues** for progress updates (instead of random chat).  

---

## 📌 Summary Example Task

**Title:** `[FE] Create Login Page`  
**Labels:** UI/UX, P1  
**Assignee:** Developer Name  
**Milestone:** Sprint-1 (Sept 01–15, 2025)  
**Start Date:** 5 Sept 2025
**Due Date:** 10 Sept 2025
**Man hrs:** 8  

---
