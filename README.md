# Microsoft 365 Coursework

Coursework from the **Cloud and Infrastructure Specialist program (EC Utbildning)** — covering Microsoft 365 administration, licensing strategy, user/group management, Exchange Online, SharePoint Online, Teams, and identity/data protection services.

---

## 📖 Overview

This repository contains two assignments and supporting material from the **M365 Cloud Services** course:

1. **Assignment 1 — Microsoft 365 Environment & Licensing** — designing a licensing plan for a 68-employee company migrating to Microsoft 365, with cost analysis and per-role license justification.
2. **Assignment 2 — SharePoint Online** — building a SharePoint site collection (`Sportstugan`) with document libraries, lists, permissions, managed metadata, a Teams environment, and a hub site.

---

## 📚 Course Content

The course covers:

- Microsoft 365 administration and Teams
- Exchange Online
- OneDrive
- SharePoint Online
- Identity and data protection services
- AI tools within Microsoft 365

**Learning outcomes practiced:**

- Managing and administering M365 accounts
- Working in the user environment
- Working with SharePoint
- Using and customizing admin centers
- Understanding licensing models
- Creating and managing groups and mailboxes
- Setting up a Teams environment
- Building a basic SharePoint intranet
- Using AI tools within M365

---

## 📝 Assignment 1 — Microsoft 365 Environment & Licensing

### Scenario
A company with 68 employees is migrating from an on-prem IT environment to Microsoft 365.

**Staff breakdown:**
- 1 IT Manager + 1 Technician
- 1 Sales Manager + 14 Sales staff
- 1 Finance Manager + 3 Finance staff
- 1 CEO + 3 Administrative staff
- 2 Warehouse staff (shared mailbox)
- 2 Drivers (plus freelancers during peak)
- Remaining staff work in the factory

### Licensing Strategy

| Role | License | Reason |
|------|---------|--------|
| IT Manager & Technician | Enterprise E3 | Advanced admin, security, and device management |
| Sales Manager & Sales Staff | Business Standard | Email, Teams, Office apps — no advanced admin needed |
| Finance Manager & Finance Team | Enterprise E3 / Business Premium | Handles sensitive financial data — needs enhanced security |
| Admin Staff & CEO | Business Standard | General administrative tasks |
| Warehouse Staff | Business Standard | Email and Teams for internal communication |
| Drivers | Business Standard | Email and Teams |
| Freelancers | Business Standard | Temporary access — sufficient |

### Cost Calculation (per user / month)

| License | Price (USD) |
|---------|-------------|
| Business Standard | $12.50 |
| Business Premium | $22.00 |
| Enterprise E3 | $36.00 |

**Monthly cost breakdown:**
- 2 × E3 = $72
- 15 × Business Standard = $187.50
- 4 × Business Premium = $88
- 4 × Business Standard = $50
- 2 × Business Standard = $25
- 2 × Business Standard = $25
- 2 × Business Standard = $25

**Total:** Calculated per month and per year, excluding VAT.

### Acquisition Procedure
1. Analyze the current IT environment and user needs
2. Select the right Microsoft 365 plan per role
3. Prepare for migration (domain readiness, email compatibility, backups)
4. Set up the M365 tenant (purchase licenses, configure domain, create accounts)

---

## 📝 Assignment 2 — SharePoint Online

### Task: Build the `Sportstugan` Site Collection

**Deliverables:**

- **Two document libraries:**
  - Customer Documents
  - Event Documents
- **One list:**
  - Training Equipment
- **At least 3 columns per app** with example items and files
- **Permissions restricted** on Event Documents to two specific users
- **A Team** created for a ski group with selected members
- **A ski facilities list** for Nordic countries
- **Site column** for Document Type with choices: Protocol, Offer, Agreement, Schedule, Information, Other
- **Managed metadata term set** with a hierarchy:
  ```
  World Regions
  ├── Asia
  └── Europe
      ├── Denmark
      ├── Finland
      ├── Iceland
      ├── Norway
      └── Sweden
          ├── Gothenburg
          ├── Malmö
          ├── Stockholm
          │   ├── Store A
          │   └── Store B
          └── Umeå
  ```
- **Term group linking:** Europe → Customer Documents + Ski Facilities; Sweden → Event Documents
- **Hub site configuration:** Sportstugan as hub, linked to Economy site collection and the ski group
- **Customized homepage:** events list, Sweden clock, useful links, news, theme color
- **Saved view** in Customer Documents showing document types sorted by location

### Work Completed

- Created the `Sportstugan` site collection
- Built Customer Documents, Event Documents, and Training Equipment
- Added example documents and list items with metadata
- Configured unique permissions on Event Documents
- Created a Team for the ski group and added members
- Built the managed metadata term set with regions and sub-locations
- Linked term groups to the correct libraries
- Configured Sportstugan as a hub site and connected associated sites
- Customized the homepage with a clock, news, and quick links
- Saved a custom view for Customer Documents sorted by location

---

## 🧰 Tools & Technologies

`Microsoft 365 Admin Center` · `Exchange Admin Center` · `SharePoint Admin Center` · `Teams Admin Center` · `SharePoint Online` · `Microsoft Teams` · `Exchange Online` · `Entra ID` · `Managed Metadata` · `Hub Sites` · `Document Libraries` · `Security Groups` · `Distribution Lists` · `Shared Mailboxes` · `Room Mailboxes` · `Licensing (E3, Business Standard, Business Premium)`

---

## 📂 Repository Structure

```
microsoft-365-coursework/
├── README.md
├── 01-licensing-and-environment/
│   ├── assignment-1.pdf
│   ├── licensing-plan.pdf
│   └── screenshots/
│
├── 02-sharepoint-online/
│   ├── assignment-2.pdf
│   ├── sharepoint-build.docx
│   └── screenshots/
│
└── 03-course-material/
    ├── course-plan.pdf
    └── m365-services-overview.pdf
```

---

## 💡 What I Learned

- Designing a licensing plan based on real business roles and security needs
- Calculating per-user and per-year costs across multiple license tiers
- Planning a migration from on-prem to Microsoft 365
- Building a SharePoint site collection from scratch with libraries, lists, and metadata
- Working with managed metadata term sets and site columns
- Configuring hub sites and associating site collections
- Managing users, groups, shared mailboxes, and room resources in the admin center
- Applying role-based admin permissions (User Administrator, Global Reader, etc.)
- Restricting access to sensitive libraries at the item and library level

---

## 🔒 Notes on Anonymization

All tenant names, domain names, email addresses, and user identities in this repository have been **anonymized** for privacy and security. Generic placeholders are used instead of real identifiers.

---

## 📄 License

This is coursework material. Feel free to use it for learning purposes.

---

*Coursework — Cloud and Infrastructure Specialist program, EC Utbildning.*
