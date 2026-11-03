# VS SAD - Sales Validation Module

## Overview
This module automates and governs the sales validation workflow for new transactions within the VS SAD (Vertical Solution - Sales Administration) platform, replacing legacy manual reporting methods with a structured, multi-tier approval system.

## Core Functions
* **Automated Queue Integration:** Automatically routes completed reservations up to the Confirm 2 stage directly into the Sales Validation menu with an initial Draft status.
* **Comprehensive Data & Financial Mapping:** Aggregates reservation details, sales personnel data, installment schedules, NPV interest settings, pricing tiers, and promotional budgets into a centralized view.
* **Mandatory & Conditional Document Attachment:** Enforces strict requirement checks for essential files—such as the Unit Reservation Form and Payment Schedule—alongside conditional IOM documents.
* **Rejection Remark & Revision Tracking:** Enables Finance & Accounting reviewers to flag errors and input specific remarks on documents, locking resubmissions until the SAD team updates the necessary files.

## Summary of Changes (To-Be vs. As-Is)
* **Workflow Digitization:** Shifted from manual reconciliation via separate reports to an integrated system workflow.
* **Dual-Tier Approval Hierarchy:** Introduced a sequential cross-departmental review process requiring approvals from SAD management followed by Finance & Accounting management.
* **Controlled Revision Cycles:** Established strict validation gates where rejected submissions require explicit remark resolution and document updates by the SAD team before re-entry.

## Business Impact & Value
* **Operational Compliance:** Eliminates unverified sales processing by enforcing mandatory document attachments and strict pre-approval gates.
* **Cross-Departmental Accountability:** Streamlines communication and accountability between Sales Administration and Finance & Accounting through transparent audit trails and remarks.
* **Data Integrity:** Protects financial margins and promotional alignment by locking final sales validations behind rigorous dual-department reviews.
