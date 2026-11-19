# BuildOps, Inc. – BuildOps Management Platform: FedRAMP Public Information

BuildOps is applying for **FedRAMP 20x Class A** certification. This repository holds the public information FedRAMP requires (CDS-CSO-PUB). It is public on purpose, so anyone can read it without signing in.

| | |
|---|---|
| Certification type | FedRAMP 20x, Class A (in process) |
| FedRAMP ID | BuildOps, Inc. - BuildOps (until FedRAMP assigns one) |
| Service model | SaaS |
| Deployment model | Public Cloud |
| Business categories | Construction, Operations Management, Customer Relations Management (CRM), Fleet Management, Finance, Analytics |
| Website | https://buildops.com/ |
| Next Ongoing Certification Report | **2027-03-12**, then every 3 months |
| FedRAMP Recognized assessment service | None (optional for Class A) |

## Service description

BuildOps is a multi-tenant, cloud-based software platform for commercial contractors and subcontractors in the mechanical, electrical, plumbing (MEP), and fire and life safety (FLS) industries. It provides one system for managing service and project work end to end: customer relationship management, quoting, dispatching and scheduling, field service and time tracking through web and mobile applications, service agreements, job costing, invoicing, payments, fleet management, and reporting.

The platform is hosted on Amazon Web Services (AWS) in the US East (N. Virginia, us-east-1) region across multiple Availability Zones, with US East (Ohio, us-east-2) held as a cold-standby recovery region. All customer data is stored in the United States. AI features are off by default for federal agency tenants and are enabled only if the agency opts in. BuildOps operates the platform under an information security program independently examined in a SOC 2 Type II report against the AICPA Trust Services Criteria for Security.

## Certified services

All services are security category **Low**.

| Service | Description |
|---|---|
| CRM | Web Application: customer, property and contact records, and the history of work for each customer and site. |
| Asset Management | Web Application: records of customer equipment and assets at each property, with service history. |
| Dispatch Board | Web Application: dispatching and scheduling of technicians and crews to jobs, visits and service calls. |
| Service and Maintenance | Web Application: service jobs and recurring maintenance work from request to completion. |
| Project Management | Web Application: construction and installation projects, including budgets, schedules, change orders and progress billing. |
| Reporting and Dashboards | Web Application: operational and financial reports and dashboards on the customer's own data. |
| Inventory & Purchasing | Web Application: parts and materials inventory, purchase orders and vendor bills. |
| Labor & Time-tracking | Web Application: capture and approval of technician time against jobs for payroll and job costing. |
| Service Agreements | Web Application: recurring maintenance contracts and the work they generate. |
| CRM+ | Add-On: sales tools on top of CRM, including quoting and proposals with delivery and approval tracking. |
| Fleet+ | Add-On: vehicle and fleet tracking for field teams. |
| Pipeline+ | Add-On: sales opportunity and pipeline management for service and project work. |
| Payments+ | Add-On: invoicing and card and bank payment collection, processed by BuildOps' payment processor. BuildOps does not store card numbers, card security codes or full bank account numbers. |
| Mobile Application | iOS and Android client used by field technicians. The installed app is a client of the in-scope cloud service; all data is processed and stored in the BuildOps cloud environment. |
| Sage Intacct | Integration: syncs accounting data between BuildOps and the customer's own Sage Intacct system, for customers who enable it. |
| QuickBooks | Integration: syncs accounting data between BuildOps and the customer's own QuickBooks system, for customers who enable it. |
| Spectrum & Vista | Integration: syncs accounting data between BuildOps and the customer's own Viewpoint Spectrum or Vista system, for customers who enable it. |
| NetSuite | Integration: syncs accounting data between BuildOps and the customer's own NetSuite system, for customers who enable it. |
| Sage 300 | Integration: syncs accounting data between BuildOps and the customer's own Sage 300 system, for customers who enable it. |
| Platform Integrations | Integration: the BuildOps public API and other connections the customer chooses to enable between BuildOps and its own systems. |

## Contacts

| Role | Contact |
|---|---|
| Accountable official | Bob Motamede, Director of IT and Information Security – bob.motamede@buildops.com |
| Security and FedRAMP | fedramp@buildops.com |
| Sales | sales@buildops.com |
| Phone | 213-559-1988 |
| Service status | https://buildops.statuspage.io |

## Documents in this repository

- `buildops-frc-cso-pkg.json` – Certification Package Overview (JSON, FedRAMP schema 2026-06-24). Direct link: https://raw.githubusercontent.com/BuildOps-Internal/fedramp-marketplace/main/buildops-frc-cso-pkg.json
- `BuildOps_FedRAMP_20x_Class_A_CPO.pdf` – the same overview in human-readable form

## Non-public documents (BuildOps Trust Center)

The SOC 2 Type II report and bridge letter, the Security Decision Record, Ongoing Certification Reports, security policies and penetration test summary are in the BuildOps Trust Center: https://trust.buildops.com. Requests from .gov, .mil and .fed.us email addresses are approved automatically, with no manual review and no NDA, for 3 months. Questions: fedramp@buildops.com.

_Last updated 2026-11-18 (Certification Package Overview version 1.4)._
