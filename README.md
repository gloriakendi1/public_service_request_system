# HudumaLink — Public Service Request System (Mini eCitizen-style)

A responsive front-end demonstration prototype for a public service request portal. It demonstrates a citizen request form, generated reference numbers, local request tracking, a basic demo administrator dashboard, and status changes.

## Features
- Submit requests with name, email, category, location, title and description.
- Generate a unique reference such as `HL-ABC1234`.
- Track a request by reference number.
- Demonstrate administrator status updates: Pending, In Progress, Resolved.
- Responsive layout for mobile and desktop.
- Basic input validation and HTML escaping for user-entered content.

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser.
3. Submit a sample request and save its reference number.
4. Track it and use the demo administrator panel to update its status.

No build step or server is required for this prototype.

## Important limitations
This is a front-end prototype for demonstration and learning, not an official government system. Demo records are stored in the current browser using `localStorage`; they are not shared between users or devices. The administrator panel is intentionally a demonstration and has no authentication. Do not enter real sensitive personal information. A production version would require a backend API, database, secure authentication and role-based access control, server-side validation, audit logging, privacy safeguards, backups, and deployment security.

## Technology
- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage for prototype data

## Suggested future improvements
- PHP/Laravel or Node.js backend with MySQL/PostgreSQL
- Authenticated citizen and administrator accounts
- Server-side request storage and tracking
- Email/SMS notifications
- Audit history and access controls
- Accessibility and security testing

## Author
Prepared as an academic portfolio demonstration. Update this section with your name and any additional project details before submission.
