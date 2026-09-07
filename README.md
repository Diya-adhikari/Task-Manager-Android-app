# Task-Manager-Android-app
**The Task Manager application featuring user authentication and comprehensive task CRUD operations.**
---
## User Authentication & Security:
Account Registration & Login: Multi-user support with registration (Full Name, Username, Password) and credential verification.
Password Security: Implemented salted SHA-256 password hashing stored securely within the local Room database.
Profile & Session Management: Dedicated profile overview displaying member details, activity statistics (total tasks, completion rates), and logout controls, alongside a one-tap Quick Demo Login for instant testing.
---
---
## Full Task CRUD Operations:
Create: Add new tasks with title, description/notes, category tagging (Work, Personal, Study, Health, Shopping, Finance, Other), priority levels (Low, Medium, High, Urgent), and due date selectors (Today, Tomorrow, Custom Date).
Read & Filter: Real-time search query filtering, category carousels, status tabs (All, Today, Pending, Completed, High Priority), and sorting by due date, priority, or creation date.
Update: One-tap completion toggle with animated strike-through styling, alongside a detailed edit dialog for updating task parameters.
Delete: Individual task deletion with an "Undo" snackbar restore action, plus a batch clear for completed tasks.
---
---
Visual Design & Architecture:
Material 3 Interface: Modern indigo and teal palette, dynamic greeting headers, interactive circular progress meters, and task statistics cards.
Room Database Persistence: Robust local SQLite architecture utilizing Room DAOs and Kotlin StateFlows for reactive data updates.
---
---
<img width="762" height="1152" alt="image" src="https://github.com/user-attachments/assets/82f21b40-8eac-4dad-ba5e-ba1bb291a7e8" />
<img width="792" height="1168" alt="image" src="https://github.com/user-attachments/assets/12686279-9549-40c4-9ebd-fb7af0bf1808" />
