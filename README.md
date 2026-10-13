# Awesome-Enterprise-Healthcare-CRM

# Top Enterprise Healthcare CRM Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Patient Engagement, Clinical Coordination & Healthcare Marketing*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Healthcare CRM**. These tools enable hospitals, health systems, payers, and life sciences organizations to manage patient relationships, coordinate care, engage populations, and optimize clinical operations.

**Examples** include Salesforce Agentforce Health (formerly Health Cloud), Veeva Vault CRM, Epic Systems, Cerner HealtheLife, Microsoft Cloud for Healthcare, Innovaccer Cured, Mercury Healthcare, Healthgrades, LeadSquared Healthcare, and Infor Healthcare (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, HIPAA-compliant workflows, and open patient management — ideal for healthcare providers, clinics, and developers seeking transparent, vendor-independent CRM solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce Agentforce Health](https://www.salesforce.com/health/)**  
  Formerly Health Cloud, now Agentforce Health. Comprehensive healthcare CRM consolidating patient and member data into a single platform. Features Patient and Member Services for appointment scheduling and benefits verification, Care Orchestration for referral management, Utilization Management for clinical data collection and medical necessity evaluation, Sales and Commercial Excellence for provider network management, and Data 360 for unified patient views. Supports FHIR R4 and USCDI standards. Includes Experience Cloud sites for patient, caregiver, and care coordinator collaboration. Compliant with HIPAA and global healthcare regulations. Available in Enterprise and Unlimited Editions .

- **[Veeva Vault CRM](https://www.veeva.com/)**  
  Industry cloud for life sciences with 190+ live customers and commitments from 14 of the top 20 biopharma companies including Amgen, Biogen, Eli Lilly, and Regeneron. Features Agentic Call Report generating Commercial Evidence to uncover treatment barriers, AI-powered engagement optimization, and connected sales-marketing-medical workflows. Part of Vault CRM Suite. Serves 1,500+ customers from largest pharma to emerging biotechs. As a Public Benefit Corporation, Veeva balances stakeholder interests .

- **[Epic Systems](https://www.epic.com/)**  
  Healthcare CRM delivered through Cheers platform and MyChart, tightly integrated within the EHR ecosystem. Embeds patient engagement, scheduling, and care coordination directly into clinical workflows. Features Patient 360 interactions within the system of record, digital front-door experiences, predictive outreach, intelligent scheduling, and next-best-action recommendations informed by longitudinal patient data. AI tools include Chart with Art (native AI charting), Ask Emmie (patient-facing AI), and Agent Factory for custom AI agents. Deep clinical-context AI within EHR, though capabilities are coupled to Epic ecosystem .

- **[Cerner HealtheLife](https://www.cerner.com/)**  
  Comprehensive web-based patient engagement service beyond a traditional patient portal. Features secure messaging with providers, direct-book appointment scheduling with request/cancel/reschedule capabilities, clinical information access (allergies, labs, radiology, pathology, health issues, immunizations, medications), online bill payment, personal health assessments with health scores, recommended health action plans with multimedia education, and health tracking for weight, activity, and nutrition. Available via web portal or iOS app. Average client acceptance rate exceeds 30%, surpassing Meaningful Use Stage 2's 5% threshold .

- **[Microsoft Cloud for Healthcare](https://www.microsoft.com/en-us/industry/health/microsoft-cloud-for-healthcare)**  
  Brings together Azure, Dynamics 365, Power Platform, and Microsoft 365 capabilities. Features patient contact center with intelligent outreach, virtual appointments, home visits, care coordination and management, remote patient monitoring, Teams for care collaboration, and unified patient view for 360-degree insights. Azure Health Data Services enables FHIR-based longitudinal patient records fueling clinical analytics, predictive modeling, and AI. Supports secure and compliant patient data handling .

- **[Innovaccer Cured](https://innovaccer.com/)**  
  Healthcare-native, AI-powered CRM scoring 90.1 in the 2026 Best in KLAS Customer Relationship Management category, exceeding the market average of 88 and earning Best in KLAS for the third consecutive year. Focuses on fast development, high configurability, and flexibility for evolving business needs. Best for health systems wanting to uncover market opportunities, know patient needs before their moments of need, engage across all channels, report with ease, and prove marketing value. Features appointment management, audience targeting, campaign management, lead qualification, marketing automation, patient communications, and physician management .

- **[Mercury Healthcare](https://mercuryhealthcare.com/)**  
  Patient engagement platform for health systems. Features appointment management, audience targeting, campaign management, and marketing automation. Cloud-based or on-premise deployment with in-person, live online, webinar, and documentation training options. Support includes email/help desk, knowledge base, phone, 24/7 live representative, and chat .

- **[Healthgrades](https://www.healthgrades.com/)**  
  CRM solution with 30+ years of continuous improvement. Features Consumer Data and predictive modeling from Healthgrades.com, Audience Insights for analyzing encounter data, demographics, and predictive models, Campaign Insights for audience-channel matching, and Insights module for on-demand reporting using business intelligence tools. Case study with Inova Fairfax Hospital achieved 10% service-utilization response rate and $803,613 ROI. As Healthgrades, data segmentation and communication campaign correlated 797 patients with $1.2M contribution margin and $24:1 ROI .

- **[LeadSquared Healthcare](https://www.leadsquared.com/)**  
  Sales and marketing automation platform with healthcare-specific solutions. Features lead capture, distribution, and high-velocity sales workflows for patient acquisition.

- **[Infor Healthcare](https://www.infor.com/industries/healthcare)**  
  Enterprise healthcare ERP and CRM solutions. Features patient relationship management, clinical operations, and financial management for healthcare providers.

## Open-Source GitHub Projects

- **[OpenHealthCRM](https://github.com/pras75299/OpenHealthCRM)**  
  Open-source healthcare operations platform (license varies) built with Next.js 16, React 19, TypeScript, Prisma 7, and PostgreSQL. Multi-tenant clinic operations with staff authentication (Auth.js) and RBAC, separate patient portal login with revocable sessions, patient management, appointments, encounters, labs, billing, payments, documents, consents, waitlist, and campaigns. Features append-only audit logging, application-layer encryption for sensitive patient fields, Server-Sent Events live vitals stream, and staff-authenticated FHIR proxy for upstream EHR integration. Docker-based local runtime with Postgres and Redis. Not presented as turnkey HIPAA-compliant production deployment but suitable for evaluation and architecture review .

- **[SuiteCRM for Healthcare](https://github.com/salesagility/SuiteCRM)**  
  Open-source CRM (AGPL-3.0) adaptable for healthcare with HIPAA-compliant architecture. Features comprehensive patient management (appointments, consultation notes, prescriptions), custom modules for patient intake, referral tracking, insurance verification, prior authorization workflows, care plan management, appointment scheduling with automated reminders via email/SMS, closed-loop referral management, care coordination for chronic conditions, patient communication campaigns segmented by demographics and conditions, and billing coordination tracking. SuiteASSURED offering provides security, warranties, and indemnities for compliance-driven industries. Case study achieved patient lifecycle metrics, no-show trend visibility, and referral source ROI dashboards with tiered role-based training driving adoption .

- **[Customermates](https://github.com/customermates/customermates)**  
  Open-source CRM (AGPL-3.0) with native MCP support for AI agents. Features contacts, organizations, deals, services, tasks, custom fields, pipelines, and dashboards. MCP endpoint enables Claude, ChatGPT, and Cursor to operate CRM directly through 50 tools. OpenAPI 3.1 REST surface with webhooks and n8n automation. Unified inbox for email, LinkedIn, WhatsApp, Instagram, and Telegram (from Pro plan). Role-based access control, audit logging. Self-hosted via Docker Compose with PostgreSQL or managed cloud with EU database region. €12/seat/month Starter pricing .

- **[nowCRM](https://github.com/nowtec/nowcrm)**  
  Open-source CRM (AGPL-3.0) with multi-channel outreach. Features Composer for email/SMS/WhatsApp campaigns, Journeys for automated touchpoints, Forms for data collection, advanced contact management, and integrations with payment providers. Swiss-hosted managed option (€299/month) with GDPR/DSG compliance. Unlimited contacts. Born from Ukraine crisis response in 2022, built to give non-profits and healthcare organizations full data sovereignty without licensing fees .

- **[Helix](https://github.com/helix-medical/helix)**  
  Free, open-source, self-hosted Patient Management System (GPL-3.0) for osteopaths. Features patient management (medical history, appointments, billing), appointment management with personal and professional calendar, billing management with invoices and Excel export, and multi-user management with roles. 100% free, open-source, and self-hosted forever. Patient data stays on your cabinet — GDPR compliant. Docker Compose installation on Linux .

- **[PatientCrm](https://github.com/dotnetappdev/PatientCrm)**  
  Open-source Patient CRM (license varies) built with .NET 10, ASP.NET Core, Blazor, and SQL Server. Features multi-role authentication (Super Admin, GP, Nurse, Receptionist, Dentist), 2FA via TOTP, passkeys via Fido2NetLib, HTTPS enforcement, secure cookie policies, and Swagger/OpenAPI documentation. Demo data includes NHS and HSCNI organizations with realistic seed data. Suitable for UK healthcare context .

- **[OpenBoxes](https://github.com/openboxes/openboxes)**  
  Open-source supply chain and logistics management (EPL-1.0) for healthcare facilities. Features inventory visibility with historical transaction records, min/max/reorder points, multi-level movement tracking, lot and serial number tracking, document management, shipping documents (Certificates of Donation, Packing Lists), grant compliance tracking, and integration with demand forecasting software. Supports SymmetricDS for bi-directional multi-server sync in low-connectivity environments. Used by hospitals and NGOs for pharmaceutical and equipment management .

- **[Twenty CRM](https://github.com/twentyhq/twenty)**  
  Modern open-source CRM (AGPL-3.0) with AI chatbot for natural language CRM queries. Features custom data models with auto-generated REST and GraphQL APIs, page context awareness for queries like "this company" or "this opportunity," and HIPAA-compliant data models structured for patient, provider, and care-team relationships .

### Additional Strong Open-Source Options

- **[OpenEMR](https://github.com/openemr/openemr)** — Open-source electronic health records and practice management (GPL-3.0) with patient portal and scheduling.
- **[HospitalRun](https://github.com/HospitalRun/hospitalrun)** — Open-source hospital information system (MIT) for offline-first healthcare.
- **[Bahmni](https://github.com/Bahmni/bahmni-core)** — Open-source hospital system for low-resource settings (GPL-3.0) combining OpenMRS and Odoo.
- Community **n8n** workflows for patient communication automation and care coordination.

**Frameworks for building custom systems**: Combine **OpenHealthCRM** or **SuiteCRM for Healthcare** as the core patient management platform with **Customermates** for AI-agent-driven CRM operations, **OpenBoxes** for supply chain integration, **Twenty CRM** for HIPAA-compliant data models, and **PostgreSQL** for persistence — creating a fully self-hosted, enterprise-grade healthcare CRM platform.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Healthcare CRMs handling protected health information must comply with HIPAA, GDPR, and other applicable regulations.
- Self-hosted open-source solutions require proper security hardening, BAA agreements where required, encryption at rest and in transit, and ongoing maintenance. Clinical data requires appropriate safeguards and compliance validation before production deployment.

---

**Made for healthcare providers, hospital administrators, care coordinators, and developers building transparent healthcare CRM solutions.**  
Let's make Enterprise Healthcare CRM more open, data-driven, and patient-centered.
