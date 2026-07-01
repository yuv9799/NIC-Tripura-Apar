---
page: send-notification
---
Design a modern, professional, and structured Notification Composer Page for administrators/authorities in the NIC Tripura APAR / ACR Management System.

**PLATFORM:** Web, Desktop-first

**PAGE STRUCTURE:**
1. **Header / Top Navbar (Consistent Branding):**
   - White navbar with NIC Tripura logo placeholder on left, app title "APAR / ACR Management System", notification bell (badge count "8"), and user profile dropdown "Dr. Amit Roy (Senior Scientist)".
2. **Left Sidebar Navigation:**
   - Deep Navy sidebar navigation panel with links and icons:
     - Dashboard
     - Employee Directory
     - Pending Reviews
     - Send Notification (Active state, highlighted in government blue)
     - Settings
3. **Main Content Area (Right of sidebar):**
   - **Page Header:**
     - Header text: "Compose Broadcast Alert"
     - Subtitle: "Draft and dispatch system-wide notices, appraisal reminders, or urgent policy updates to employees."
   - **Composer Form Container (Card):**
     - A clean white surface card enclosing the form elements:
       - **Section 1: Target Audience & Priority:**
         - Dropdown Selection: "Recipient Group" (options: All Registered Employees, Software Development Department, Infrastructure & SDC Cell, Specific Designation, or Search Individual Employee).
         - Radio Button Cards (Priority Levels):
           - "Normal" (Muted styling, info circle icon)
           - "High" (Orange border, warning icon)
           - "Emergency" (Red border, pulsing warning icon, triggers desktop alert banner)
       - **Section 2: Alert Category & Metadata:**
         - Dropdown Selection: "Category" (options: APAR Timeline Reminder, System Upgrades & Maintenance, Policy Circulars, General Notice).
         - Text Input: "Subject / Title" (placeholder: "e.g., Final Extension of APAR Self-Appraisal Submission Timeline").
       - **Section 3: Message & Attachments:**
         - Rich Text Area: "Message Details" (Generous height, placeholder: "Type your announcement or detailed instructions for the personnel...").
         - Drag-and-drop file upload zone: "Attach Supporting Documents (PDF only, Max 10MB)".
       - **Form Actions Row:**
         - A checkbox: "Send copy as SMS/Email alert to target users."
         - Row containing:
           - "Dispatch Alert" button (Primary action, Interactive Blue with send/telegram icon)
           - "Save Template" button (Secondary action, border button)
           - "Cancel" button (Text link, redirects to Dashboard)
4. **Footer:**
   - "Designed & Developed by National Informatics Centre, Tripura State Centre. Copyright © 2026. All Rights Reserved."

**DESIGN SYSTEM (REQUIRED):**
When generating screens, do not reference CSS styles directly in text prompts. The project design theme handles these tokens. Use structural prompts targeting:
*   Header: White top navbar with NIC Logo placeholder and Notification Bell.
*   Sidebar Navigation: Left-docked navigation using Lucide icons.
*   Cards: White rectangular panels with 8px rounded corners and thin border.
*   Tables: Structured columns with status badges (Green for Approved, Yellow for Pending, Red for Rejected).
