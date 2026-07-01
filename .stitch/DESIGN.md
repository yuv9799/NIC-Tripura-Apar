# Design System: NIC Tripura APAR / ACR Management System
**Project ID:** 14307320087204588774

## 1. Visual Theme & Atmosphere
The interface is designed to evoke a modern, trustworthy, and highly structured government portal. It balances official administrative utility with a clean, accessible, and responsive user experience. It avoids visual clutter, opting for generous whitespace, distinct sections, and clear semantic states.

## 2. Color Palette & Roles
*   **Government Blue (`#0B5CAD`):** The primary color, used for the main brand elements, active navigation links, and administrative highlights.
*   **Interactive Blue (`#2563EB`):** The secondary color, used for links, interactive components, hover states, and standard action buttons.
*   **Success Green (`#10B981`):** The accent color, representing completion, high grades, approved statuses, and success indicators.
*   **Warning Orange/Amber (`#F59E0B`):** Used for pending reviews, flagged submissions, and action-required alerts.
*   **Destructive Red (`#EF4444`):** Used for rejected statuses, error states, and critical alerts.
*   **Off-White Background (`#F8FAFC`):** The default screen background, creating a soft, accessible backdrop that minimizes glare.
*   **Pure White Surface (`#FFFFFF`):** Used for content cards, data tables, and modal dialogs to establish clear layered hierarchy.
*   **Dark Slate Text (`#111827`):** The primary text color for maximum readability and contrast.
*   **Deep Navy Sidebar (`#0A1E3F`):** Used for the side navigation panel, giving the application an authoritative, structured government portal header look.

## 3. Typography Rules
*   **Font Family:** Inter (via Google Fonts)
*   **Headings:** Space and breathing room around titles. Semi-bold and bold weights are used to clearly structure page sections.
*   **Body Text:** Regular weight, sized and spaced for optimal legibility, especially inside dense forms and data tables.

## 4. Component Stylings
*   **Buttons:** Softly rounded corners (`border-radius: 8px`). Primary buttons use Government Blue (`#0B5CAD`) or Interactive Blue (`#2563EB`) with white text. Secondary buttons use transparent or white backgrounds with light gray borders.
*   **Cards/Containers:** Pure white surface (`#FFFFFF`) with a subtle border (`#E5E7EB`) and soft, diffused light shadow (`box-shadow: 0 1px 3px rgba(0, 0, 0, 0.1)`) to stand out from the Off-White Background (`#F8FAFC`).
*   **Sidebar:** Deep Navy (`#0A1E3F`) backdrop, contrasting against the clean white navbar and main page content. Active links are highlighted using a subtle left border or background accent in Government Blue (`#0B5CAD`).
*   **Inputs/Forms:** Input fields are outlined with a light gray border (`#E5E7EB`), turning to Interactive Blue (`#2563EB`) on focus, with generous padding for easy typing.
*   **Data Tables:** Modern tables with white background, subtle gray borders, and alternating light gray rows (`#F9FAFB`) for readability. Column headers are semi-bold and clean.

## 5. Layout Principles
*   **Desktop-First / Responsive:** Designed for standard government desktop monitor setups, scaling down cleanly to tablet and mobile screens.
*   **Generous Spacing:** Spacing should be open and comfortable, preventing the dense bureaucratic feel typical of legacy portals.
*   **Grid Alignment:** Standard 12-column grid alignment for dashboard metrics, form layouts, and directories.

## 6. Design System Notes for Stitch Generation
When generating screens, do not reference CSS styles directly in text prompts. The project design theme handles these tokens. Use structural prompts targeting:
*   Header: White top navbar with NIC Logo placeholder and Notification Bell.
*   Sidebar Navigation: Left-docked navigation using Lucide icons.
*   Cards: White rectangular panels with 8px rounded corners and thin border.
*   Tables: Structured columns with status badges (Green for Approved, Yellow for Pending, Red for Rejected).
