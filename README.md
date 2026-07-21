# Jamaludin Dipa - Portfolio

Portfolio website showcasing internal systems, manufacturing applications, and security infrastructure projects.

## Live Preview

View the portfolio at: `https://jamaludindipa.github.io/portfolio/`

## Project Structure

```text
jamalgithub/
├── index.html
├── projectimg/
│   ├── MES Traceability/
│   ├── MOM/
│   ├── APDM/
│   ├── Ceklist/
│   ├── IT Ticket/
│   ├── Production Stamping/
│   ├── OEE Welding/
│   ├── Ai Camera Inspection/
│   ├── Engineering Data/
│   ├── Ik Digital/
│   └── IT Security/
├── README.md
└── package.json
```

## Featured Project

### META - Manufacturing Execution & Traceability Application

#### Overview

META is a Manufacturing Execution System designed to connect work order execution, material readiness, stamping production, real-time OEE, WIP supermarket, welding assembly, final inspection, finish good flow, delivery, and upstream-downstream traceability in one operational manufacturing platform.

#### Business Problem

- Production work orders are difficult to trace from raw material to finish good.
- Production, OEE, warehouse movement, and inspection data are often separated across different operational views.
- Material, WIP, and FG movement require validated scan, picking, check, and movement print flows.
- Part tag traceability must connect raw material, WIP, production, final inspection, finish good, and delivery events.
- Operational UI needs to stay consistent across multiple manufacturing modules.

#### Key Features

- Modular Laravel Blade UI for MES, warehouse, quality, and traceability workflows.
- Role-based menu visibility with a sidebar-driven dashboard structure.
- Reusable movement flow covering request, picking, check OK, and movement print.
- QR and part-tag oriented traceability flow.
- End-to-end dummy data simulation for manufacturing process validation.
- UI parity across modules using a shared topbar, sidebar, and main content pattern.

#### Module Map

- Dashboard & Monitoring: MES Dashboard, MES Dashboard Menu, Machines Real-time, PLC Monitor, OEE Report, Pareto Loss, Six Big Loss
- Work Order & Production: Work Order Stamping, Work Order Welding Assy, Job Order / Job Card, Stamping Manual Production, Stamping OEE Production, Welding Assy Manual Production
- Warehouse & Movement: RM Warehouse, Material Movement, WIP Supermarket Warehouse, WIP Supermarket Movement, FG Warehouse & Delivery
- Quality: Raw Material Inspection, Final Inspection, FI Lot Inspection, FI Movement, Hold / Disposition
- Traceability: Traceability Upstream Downstream, Document Type & Sequence, Scan Event Flow, Stock Card / Movement History

#### End-to-End Manufacturing Flow

`ERP / APS Work Order -> Material Inspection -> RM Stock Ready -> Bon Material / Material Request -> Material Picking & Check OK -> Receipt Material Production -> Job Card Execution -> Manual / OEE Production Output -> Stamping Movement -> WIP Supermarket / Final Inspection -> FI Lot Inspection -> FI Movement -> FG Warehouse -> Delivery -> Traceability Upstream Downstream`

#### Tech Stack

- Backend: Laravel 11, PHP 8.3
- Frontend: Blade, JavaScript, Tailwind CSS
- Database: MySQL
- Testing: Playwright
- Deployment: GitLab, Linux Server, systemd

#### Screenshots

Recommended views shown in this repository:

- Login page META
- MES Dashboard
- MES Dashboard Menu
- Work Order Stamping
- Bon Material / Material Request
- Material Movement
- Stamping Movement
- WIP Supermarket Movement
- Welding Assy Movement
- Final Inspection FIFO
- FG Delivery Stock
- Traceability Upstream Downstream

#### Current Status

- Status: Internal MES MVP
- Focus: Frontend flow, module architecture, UI consistency, manufacturing process simulation
- Next phase: Backend transaction service, database normalization, scan validation service, and production-grade traceability event store

#### Security & Privacy Notice

Screenshots and data shown are sanitized or dummy data. Internal credentials, database configuration, company private endpoints, and production secrets are excluded.

#### Portfolio Summary

Built a modular MES and Traceability system for automotive metal manufacturing, covering work order execution, OEE integration, warehouse movement, WIP supermarket, quality inspection, finish good delivery, and upstream-downstream traceability using Laravel Blade, JavaScript, and Playwright validation.

## Other Projects

- MOM (Minute Of Meeting Online)
- Automatic Preventive Dies Maintenance
- Ceklist Management System
- IT Ticket Management
- Aplikasi Stamping
- OEE Welding Single Product
- AI Camera Inspection QC Check
- Engineering Data Project Masspro
- IK Digital
- IT Security Infrastructure

## Technologies Used In This Portfolio

- Frontend: HTML5, Tailwind CSS, JavaScript, Font Awesome
- Portfolio runtime: Static site hosted on GitHub Pages
- Tooling: Node.js, Puppeteer

## Contact

- GitHub: [@jamaludindipa](https://github.com/jamaludindipa)
- LinkedIn: [Jamaludin Dipa](https://www.linkedin.com/in/jamaludin-dipa-1660ba107/)
- Email: `jamaludinsa@gmail.com`
