# FDRIntelligence
# FINTRACK – Smart Security Deposit / FDR Management Portal

### Smart India Hackathon 2026 | Problem Statement ID: 26265

**Team Name:** FinTrack Innovators  
**Theme:** Smart Automation  
**Category:** Software

---

## 📌 Project Overview

FINTRACK is an intelligent, centralized web-based portal designed to streamline the management of security deposits and Fixed Deposit Receipts (FDRs) submitted by educational institutions.

The system automates FDR record management through OCR-based document extraction, automated data validation, maturity-date monitoring, discrepancy detection, and priority-based case management.

It provides a unified platform for institutions and authorized officials to manage FDR submissions, verification, renewals, replacements, and release requests while maintaining secure records and complete administrative traceability.

FINTRACK aims to transform fragmented manual FDR tracking into a centralized, automated, and transparent digital workflow.

## 🚨 Problem Statement

Traditional FDR management involves several manual and disconnected processes, creating administrative difficulties.

Major challenges include:

- Fragmented institution-wise FDR records.
- Manual document scrutiny and repetitive data entry.
- Difficulty identifying missing or mismatched information.
- Manual maturity-date tracking.
- Missed deadlines and delayed renewals.
- Email-based follow-ups.
- Limited visibility into pending and urgent cases.
- Difficulty maintaining complete instrument histories.

These challenges increase administrative workload and make FDR lifecycle management less efficient.

## 💡 Proposed Solution

FINTRACK introduces a Smart FDR Management Portal that combines document automation, intelligent validation, deadline monitoring, and centralized administrative workflows.

The proposed solution includes:

1. **Centralized FDR Repository:** Securely maintains institution-wise FDR records.
2. **AI-Powered OCR Extraction:** Extracts relevant information from uploaded FDR documents.
3. **Smart Discrepancy Detection:** Identifies missing, duplicate, and mismatched information.
4. **Automated Maturity Monitoring:** Tracks maturity dates and generates renewal reminders.
5. **Priority-Based Management:** Highlights urgent and pending cases using explainable priority rules.
6. **Instrument Lifecycle Tracking:** Maintains linked histories of renewals and replacements.
7. **Audit Trail:** Records verification, updates, and approvals.
8. **Automated Workflow Management:** Streamlines verification, renewal, and release requests.

## ✨ Key Features

### 1. Centralized Dashboard
- Consolidated institution-wise FDR records.
- Overview of active, expiring, matured, and pending instruments.
- Centralized monitoring of FDR status.

### 2. OCR-Based Document Extraction
- Upload FDR documents digitally.
- Extract relevant information using Tesseract OCR.
- Convert document information into structured records.
- Reduce repetitive manual data entry.

### 3. Automated Data Validation
- Identify missing information.
- Detect duplicate records.
- Flag mismatched information.
- Support official verification.

### 4. Smart Maturity Monitoring
- Monitor FDR maturity dates.
- Generate automated renewal reminders.
- Support escalation for pending cases.
- Improve deadline management.

### 5. Priority-Based Case Management
- Identify urgent and pending records.
- Apply explainable priority-scoring rules.
- Help officials prioritize administrative work.

### 6. Instrument History Tracking
- Link original FDR records with renewals.
- Maintain replacement instrument histories.
- Preserve administrative decisions and updates.

### 7. Secure Administration
- JWT-based authentication.
- Role-Based Access Control (RBAC).
- Input validation.
- Audit logging and status history.

## 🏗️ System Architecture

FINTRACK follows a modular architecture consisting of the following layers:

**User Interface**
- Institution User
- Authorized Officer

**Frontend Layer**
- React
- Vite
- Tailwind CSS

**Backend Layer**
- Python
- FastAPI
- Pydantic
- REST APIs

**Intelligence Layer**
- OCR-based field extraction
- Explainable priority scoring
- Maturity alerts and escalation

**Database and Storage Layer**
- PostgreSQL / SQLite
- FDR records
- Instrument history
- Protected document storage

## 🔄 System Workflow

1. **FDR Upload:** Institutions upload FDR documents through the portal.
2. **Information Extraction:** OCR extracts relevant information from uploaded documents.
3. **Data Validation:** The system checks for missing, duplicate, and mismatched information.
4. **Official Review:** Authorized officials review extracted details and flagged discrepancies.
5. **Lifecycle Tracking:** The system monitors FDR maturity, renewals, and replacements.
6. **Automated Alerts:** Notifications and escalation rules highlight cases requiring attention.
7. **Administrative Processing:** Officials manage verification, renewal, and release requests.
8. **Audit and Storage:** Records, updates, approvals, and instrument histories are securely maintained.

## 🛠️ Technology Stack

| Layer | Technologies |
|---|---|
| Frontend | React, Vite |
| UI Styling | Tailwind CSS |
| Backend | Python, FastAPI |
| Data Validation | Pydantic |
| API Communication | REST APIs |
| Database | PostgreSQL / SQLite |
| OCR Engine | Tesseract OCR |
| Document Processing | PDF and Image Processing |
| Authentication | JWT |
| Authorization | Role-Based Access Control |
| Monitoring | Scheduled Checks and Notifications |
| Accountability | Audit Logging |

## 🎯 Expected Benefits

- Reduced repetitive manual work.
- Improved accuracy in FDR record management.
- Faster document review and validation.
- Timely maturity reminders and renewal follow-ups.
- Better visibility into urgent and pending cases.
- Improved traceability of renewals and replacements.
- Increased administrative transparency.
- Secure and centralized information management.

## 📊 Evaluation Metrics

The proposed system can be evaluated using:

- Discrepancy Detection Precision.
- Discrepancy Detection Recall.
- Average Case Review Time.
- Reminder and Escalation Accuracy.
- Instrument-History Linking Percentage.
- Unauthorized-Access Prevention Rate.
- Reduction in Manual Tracking Effort.

## 🚀 Feasibility and Scalability

FINTRACK uses established open-source technologies, making prototype development practical and cost-effective.

The initial prototype can use synthetic FDR records and sample documents to demonstrate OCR extraction, validation, maturity monitoring, and administrative workflows.

Its modular architecture supports future expansion across multiple institutions and authorized offices.

Bank and AICTE system integrations will depend on obtaining the required authorized access.

## 🔮 Future Enhancements

- Integration with authorized banking verification services.
- Integration with institutional and regulatory platforms, subject to access permissions.
- Enhanced OCR for different FDR document formats.
- Advanced reporting and analytics.
- Expanded notification channels.
- Configurable institutional approval workflows.

## 📚 References

1. [AICTE Approval Process Handbook](https://www.aicte.gov.in/sites/default/files/APH%20Final.pdf)
2. [Document Information Extraction Using OCR](https://doi.org/10.1016/j.procs.2022.09.214)
3. [AI and Automation for Financial Document Processing](https://doi.org/10.3390/electronics12040939)
4. [AICTE Approval Process Guidelines](https://indiankanoon.org/doc/173919027/)
5. [Press Information Bureau – Government of India](https://www.pib.gov.in/Pressreleaseshare.aspx?PRID=1983013&lang=2&reg=48)
6. [NIST Security and Privacy Controls – SP 800-53](https://csrc.nist.gov/pubs/sp/800/53/r5/upd1/final)

---

## 👥 Team – FinTrack Innovators

**Project:** FINTRACK – Smart Security Deposit / FDR Management Portal

**Hackathon:** Smart India Hackathon 2026

**Problem Statement ID:** 26265

**Theme:** Smart Automation

---

**FINTRACK – From Fragmented Tracking to Proactive, Traceable FDR Lifecycle Management.**
