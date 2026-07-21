# Jamaludin Dipa - Portfolio

Portfolio website showcasing manufacturing systems, internal business applications, AI and computer vision workflows, and security infrastructure projects.

## Live Preview

View the portfolio at: `https://jamaludindipa.github.io/portfolio/`

## Portfolio Focus

This portfolio brings together the main project areas currently presented on the site:

- Manufacturing systems: MES traceability, stamping operations, OEE, warehouse movement, and inspection flows
- Business applications: meeting management, checklist workflows, maintenance systems, and IT ticketing
- AI and data workflows: AI camera inspection, agent orchestration, and engineering data management
- Security infrastructure: Wazuh, Shuffle, Iris, and MISP based security environment

## Project Highlights

### Manufacturing & Operations

- `META - Manufacturing Execution & Traceability Application`
  Integrated MES flow covering work order execution, material readiness, warehouse movement, quality inspection, finish good delivery, and upstream-downstream traceability.
- `Aplikasi Stamping`
  Production dashboard and manufacturing reporting flow for stamping operations.
- `OEE Welding Single Product`
  Real-time welding effectiveness monitoring with manufacturing analytics and PLC-oriented operational visibility.
- `Automatic Preventive Dies Maintenance`
  Preventive maintenance workflow for dies with scheduling, monitoring, and maintenance execution support.

### Internal Business Applications

- `Mom (Minute Of Meeting Online)`
  Laravel and React based meeting management system for scheduling, documentation, and collaborative meeting minutes.
- `Ceklist Management System`
  Checklist, planner, and task control application for routine operational activities.
- `IT Ticket Management`
  Internal IT ticketing workflow with operational tracking and support handling.
- `IK Digital`
  Digital internal platform for documentation and knowledge distribution.

### AI, Data, and Security

- `AI Camera Inspection QC Check`
  Computer vision driven inspection workflow for quality control scenarios.
- `Engineering Data Project Masspro`
  Centralized engineering data management workflow for operational access and organization.
- `IT Security Infrastructure`
  Security deployment portfolio covering SIEM, SOAR, threat intelligence, and security operations tooling.

## Featured Manufacturing Project

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

- Modular Laravel Blade UI for MES, warehouse, quality, and traceability workflows
- Role-based menu visibility with sidebar-driven navigation
- Reusable movement flow covering request, picking, check OK, and movement print
- QR and part-tag oriented traceability flow
- End-to-end manufacturing simulation with consistent operational data
- UI parity across modules using shared topbar, sidebar, and main content patterns

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

#### Current Status

- Status: Internal MES MVP
- Focus: Frontend flow, module architecture, UI consistency, and manufacturing process integration
- Next phase: Backend transaction service, database normalization, scan validation service, and production-grade traceability event store

#### Security & Privacy Notice

Screenshots and data shown are sanitized or dummy data. Internal credentials, database configuration, company private endpoints, and production secrets are excluded.

## Technologies Used In This Portfolio

- Frontend: HTML5, Tailwind CSS, JavaScript, Font Awesome
- Backend and application stack across showcased systems: Laravel, PHP, React, Python, Flask, MySQL
- AI and inspection stack: OpenCV, YOLO, agent orchestration workflows
- Security stack: Wazuh, Shuffle, Iris, MISP
- Tooling: Node.js, Puppeteer, GitHub Pages

## Repository Structure

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

## Contact

- GitHub: [@jamaludindipa](https://github.com/jamaludindipa)
- LinkedIn: [Jamaludin Dipa](https://www.linkedin.com/in/jamaludin-dipa-1660ba107/)
- Email: `jamaludinsa@gmail.com`
