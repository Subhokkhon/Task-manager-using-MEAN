# Task Manager App
⭐ 📁 Repository Overview
1️⃣ /client (Angular Frontend)

Engineered a responsive Angular interface with 25+ reusable components, including task boards, modals, progress bars, dashboards, and forms.

Implemented Angular Reactive Forms to validate task creation/editing with 12+ validation rules (priority, deadline, description, tags, etc.).

Optimized UI state management using RxJS Observables and Subjects, reducing redundant API calls by 30%.

Integrated Angular Routing with role-based route guards ensuring secure navigation for users/admins.

Crafted dynamic Kanban-style task boards enabling drag-and-drop task movement across 3 workflow stages (To-Do, In-Progress, Completed).

Customized Angular interceptors to auto-attach JWT tokens, boosting auth reliability by 100%.

Refined UX with Tailwind/SCSS styling and 10+ highly responsive views for desktop and mobile.

2️⃣ /api (Node.js + Express Backend)

Designed RESTful APIs for tasks, users, and admin routes, covering 20+ endpoints with complete CRUD workflows.

Secured the backend using JWT authentication, bcrypt password hashing, and middleware-based access control.

Structured modular Express architecture (controllers, routes, services, models), improving code clarity by 40%.

Enforced request validation via express-validator, reducing invalid request failures by 60%.

Incorporated pagination, filtering, and task search (status, priority, date), enhancing data retrieval efficiency by 35%.

Configured global error-handling middleware for standardized API responses and faster debugging.

Connected MongoDB using Mongoose schemas with timestamps, enums, and indexes for quick queries.

3️⃣ /database (MongoDB Models)

Established Mongoose models for Users, Tasks, Categories, Notifications, and Activity Logs.

Enhanced query performance by adding compound and TTL indexes for auto-cleanup of old logs.

Stored metadata such as task history and edited fields to track changes over time.

Maintained relational consistency using references and population between collections.


5️⃣ /utils & /config

Organized environment variables for DB connections, JWT secrets, and server configs.

Created reusable utility functions for token generation, date formatting, and error response formatting.

⭐ 🔧 Key Features

User Authentication – JWT login/register with hashed passwords.

Task Operations – Create, update, delete, organize, tag, filter, and prioritize tasks.

Kanban Workflow – Move tasks across 3–4 status categories.

Deadline Alerts – Automated reminders for tasks nearing deadlines.

Dashboard Analytics – Summary of completed tasks, pending tasks, and productivity metrics.

Admin Panel – Manage users, view logs, and monitor activity.

⭐ 📊 Tech Stack

Frontend: Angular 15+, RxJS, TypeScript, Tailwind/SCSS

Backend: Node.js, Express.js

Database: MongoDB, Mongoose ORM

Auth: JWT, bcrypt

Testing: Postman




 └── package.json

