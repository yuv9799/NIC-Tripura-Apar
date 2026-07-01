# Site Specification: NIC Tripura APAR / ACR Management System
**Project ID:** 14307320087204588774

## 1. Vision & Goals
A modern, accessible, and structured Web Portal for employees and reporting authorities at NIC Tripura to manage the Annual Performance Assessment Reports (APAR) and Annual Confidential Reports (ACR).

## 2. Target Audience
*   **Employees (NIC Tripura staff):** To submit self-appraisals, track submission timeline, and receive status notifications.
*   **Reporting Authorities / Reviewers:** To view employee directories, assess targets and achievements, assign grades, and approve/reject/request resubmission.

## 3. Technology Stack
*   **Design & Layout:** Google Stitch
*   **Frontend Export:** React, Vite, Tailwind CSS, TypeScript, Lucide Icons, Inter Font.

## 4. Sitemap (Screens Checklist)
- `[x]` **login:** Login Page (Unified government portal entry)
- `[x]` **register:** Employee Registration Form
- `[x]` **employee-dashboard:** Employee dashboard with welcome card, status, timelines, quick actions
- `[x]` **authority-dashboard:** Authority dashboard with overview metrics, charts, pending reviews
- `[x]` **directory:** Employee directory with searchable/filterable table, actions (View, Edit, Deactivate, Send Reminder)
- `[x]` **apar-submit:** APAR Submission Page (targets, achievements, draft, submit, progress steps)
- `[x]` **apar-review:** APAR Review Page (targets, achievements, grade dropdown, flag checkbox, resubmission request, action logs)
- `[x]` **notifications:** Notification Center (dropdown lists, badges, category filters)
- `[ ]` **send-notification:** Notification Composer page (audience target, message, priorities)
- `[ ]` **profile:** User Profile page (info, security, log)
- `[ ]` **settings:** App Settings page (theme, system settings, preference configs)
- `[ ]` **errors:** Custom Error states / views (403, 404, 500)
- `[ ]` **loading-states:** Skeleton loader designs
- `[ ]` **empty-states:** Professional illustrations/layouts for empty queues
- `[ ]` **success-dialog:** Government-style success confirmation overlay

## 5. Design Roadmap
1. **Initial setup:** Configure colors, fonts, roundness (Completed)
2. **Phase 1 (Access Control):** Login, Employee Registration (Completed)
3. **Phase 2 (Employee Flow):** Employee Dashboard (Completed), APAR Submission Page, User Profile
4. **Phase 3 (Authority Flow):** Authority Dashboard (Completed), Employee Directory (Completed), APAR Review Page
5. **Phase 4 (System & Alerts):** Notification Center, Send Notification Page, Settings Page
6. **Phase 5 (Utilities):** Error Pages, Loading/Skeleton States, Success/Empty dialogues
