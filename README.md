# MedCare Hospital ERP Demo (React)

A responsive front-end prototype based on the supplied MedCare ERP dashboard reference.

## Run locally
1. Install Node.js 18+.
2. Open this folder in a terminal.
3. Run `npm install`
4. Run `npm run dev`
5. Open the local URL printed by Vite (usually http://localhost:5173).

## Included demo workflows
- Dashboard KPIs, live alerts, revenue chart and patient distribution
- Patient directory search and patient registration modal (adds a row in local React state)
- Appointments, OPD, IPD/bed management, EMR, lab, radiology, pharmacy, billing, insurance, OT, nursing, blood bank, inventory, assets, HR, reports and settings navigation
- Responsive sidebar and mobile layout

## Important
This is a front-end demo using fictional sample data. It is not connected to a backend, real patient records, clinical devices, payment gateways, or hospital systems. Do not enter real patient or health information.

## Suggested production architecture
React + TypeScript, Node.js/NestJS APIs, PostgreSQL, role-based access control, audit logging, encryption, backups, and standards-based integrations (HL7/FHIR, DICOM/PACS). A production deployment requires clinical workflow validation, security review, privacy/legal compliance, and testing.
