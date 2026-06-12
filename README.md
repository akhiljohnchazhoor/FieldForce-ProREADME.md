Engineering Case Study: FieldForce-Pro Core Modules

Company: Bairuha Tech  

Role: Software Engineering Intern  

Project: Develop a Comprehensive Field Service Management Application 

*Note: This repository serves as an architectural overview and technical case study. The original source code is proprietary to Bairuha Tech and remains in a private repository. The algorithms, system designs, and data structures discussed here represent my personal contributions and problem-solving approaches.*

---

## 🧰 Tech Stack

- **Frontend:** React, TypeScript
- **Mobile:** React Native (Expo)
- **Backend / Database:** PostgreSQL
- **DevOps & Tooling:** Docker, Git & GitHub

---

## ✨ Key Features & Contributions

### 👥 Customer Management Module
- Engineered new `Assets` and `Maintenance Plan` data fields.
- Redesigned the `Company Details` and `Contact Details` UI/UX following Zoho-style design principles.
- Enhanced the `Create Contact` workflow with dynamic company linking and separate Service / Billing addresses.
- Established backend database links between Customer Management and dependent modules.

### 📍 Live GPS Tracking
- Implemented real-time GPS tracking of technicians within the FSM platform.

### 📄 Service Agreement & SLA Engine
- Integrated the Service Agreement Module across web and mobile with cross-platform data synchronization.
- Built synchronized SLA tracking with real-time timers and a dynamic countdown mechanism in the Work Order grid.
- Created SLA Policies (Response & Completion) with multi-language translation support.
- Engineered a real-time alert system for SLA breaches and technician request acceptance/rejection.

### 🤖 AI Diagnostics
- Integrated an AI-powered diagnostic module into the platform's core.

### 🔁 Data Integrity Tooling
- **Merge / Deduplication Engine:** Combined duplicate records by reparenting child entities (Work Orders, Invoices) to a master record with soft-delete on duplicates.
- **Change Owner:** Reassigned record ownership individually and in bulk via table selection.
- **Asset Cloning:** Cloned assets while preserving parent and service-location relationships.

### 📊 Bulk Data Operations
- **CSV Import:** Mapped and upserted large datasets directly into the system.
- **CSV Export:** Exported filtered records into clean, formatted CSV files with professional English headers.

### 🛠️ Reliability, Performance & QA
- Resolved a fatal PostgreSQL crash by restricting eager-loaded attributes during API calls.
- Fixed silent frontend crashes and TypeScript build-breaking interface mismatches.
- Resolved Insights dashboard aggregation bugs (Enum mismatches, correct exclusion logic).
- Handled complex Git merge conflicts and synchronized with remote branches.
- Conducted end-to-end functional validation across web and mobile (via Expo Go).

---

## 🐳 Development Environment
- Containerized the local development environment using **Docker**.
- Managed version control and feature branches using **Git & GitHub**.

---

## 🙏 Acknowledgements
Grateful to the team at **Bairuha Tech** for the mentorship and the opportunity to contribute to real-world, production-grade software.
