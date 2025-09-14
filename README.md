# SaasDashboard
UI/UX for dashboard app
SaaS Contracts Dashboard

A React + TailwindCSS based dashboard to manage contracts.
The app provides:

Secure login (mock authentication),

Contract list with search, filters, and pagination,

Detailed contract view with clauses, AI insights, and evidence,

File upload modal with simulated uploads,

Fully responsive design ready for deployment.

Features
1. Authentication

Login with any username.

Password must be test123.

On successful login, a mock JWT token is stored in localStorage.

Logout clears session.

2. Dashboard

Sidebar Navigation:

Contracts

Insights

Reports

Settings

Topbar:

Search contracts by name or party.

Logout button and profile avatar.

Contracts Table:

Displays Contract Name, Parties, Expiry Date, Status, and Risk.

Search, filter, and paginate through contracts.

Click a contract to open detailed view.

3. Filters

Status Filter:

Active

Expired

Renewal Due

Risk Filter:

Low

Medium

High

4. Contract Detail Page

Each contract has:

Metadata:

Title

Parties

Start & Expiry Dates

Status

Risk

Clauses Section:

Clause title

Summary

Confidence score bar

AI Insights:

List of risks and recommendations with severity coloring (High, Medium, Low).

Evidence Drawer:

Slide-in panel with source text and relevance scores.

5. Upload Modal

Drag & Drop or Browse to select files.

Files simulate upload with random delay.

Status indicators:

Uploading

Success

Error (optional future implementation).

6. Responsive Design

Sidebar collapses on smaller screens.

Table scrolls horizontally on mobile.
