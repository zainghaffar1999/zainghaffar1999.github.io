# OBS-Demo
OBS Admin Panel — Frontend Demo
A frontend demo replica of a real ERP/CRM admin panel I built professionally as a MERN Stack Developer. All data is mocked client-side — no backend or API keys required. Just open the HTML file in any browser.

Live Preview

Open index.html directly in your browser — no installation needed.

Demo credentials (pre-filled):

Email: admin@obs.com
Password: admin123


What's Inside
This is a single-file, fully interactive admin dashboard that demonstrates production-level frontend engineering across several complex modules:
Sales CRM & Funnel

Visual sales funnel with stage-by-stage conversion rates
Kanban pipeline board with lead cards, scores, and priority indicators
Full lead detail slide-over with stage movement, quick actions, and activity feed
Lead source and partner breakdown analytics

Billing & Invoicing

Sale orders with multi-invoice support per order
Invoice creation modal with dynamic charge modules (discounts, tax, shipping)
Payment recording per invoice (GAAP-compliant — payment → invoice, not order)
Client credit balances with apply-to-invoice workflow
Printable/downloadable customer invoice view with partial invoice support
Email invoice composer with auto-filled recipient, CC, and body

Remediation Operations

90-day number remediation lifecycle tracker
Batch management with timeline progress bars and milestone triggers (Day 45 / Day 90)
Full number registry table with carrier scoring (AT&T, T-Mobile, Verizon labels)
ANI monitoring dashboard with partner feed access management
Batch filtering, sorting, and live search

Infrastructure

SIP Trunk management with approval workflow
Trunk health monitoring and channel tracking

Client & Partner Management

Full client table with search, filter, and detail slide-over
Client detail page with agreements, assigned products, onboarding progress
Partner/reseller management with commission tracking

System & Settings

Integrations hub (QuickBooks, Metabase, VoiceAlerts)
OBS settings modal with cascading feature toggles (SIP → Remediation dependency)
Billing settings with dynamic charge module builder


Technical Highlights

Zero dependencies — no framework, no build step, no npm
Chart.js for revenue and ANI call volume charts
CSS design system with custom tokens, semantic color ramps, and full light/dark mode support
Component patterns — modals, slide-overs, toasts, tab bars, kanban columns, data tables, stat cards
Live filtering & search across all data tables without page reloads
Fully interactive — add invoices, record payments, apply credits, move lead stages, approve SIP trunks, trigger batch milestones
Responsive with mobile breakpoints


Stack
LayerTechnologyMarkupHTML5StylingVanilla CSS with custom design tokensLogicVanilla JavaScript (ES6+)ChartsChart.js 4.4FontsGoogle Fonts (DM Sans, DM Mono)

Context
This demo is a replica of real production work I completed as a MERN Stack Developer at NoveltySoft Pvt Ltd, where I built and maintained CRM and ERP systems. The original system runs on a full MERN stack (MongoDB, Express, React, Node.js) with MySQL for relational data, REST APIs, JWT authentication, and CI/CD pipelines via Git.
This frontend-only version was built to demonstrate my UI engineering and product thinking without exposing any proprietary code or client data.

About Me
Zain Bin Ghaffar — MERN Stack Developer based in Lahore, Pakistan

Email: zainbinghaffar@gmail.com
LinkedIn: www.linkedin.com/in/zain-ghaffar-17b562183
Portfolio: https://zain-ghaffar.netlify.app/
