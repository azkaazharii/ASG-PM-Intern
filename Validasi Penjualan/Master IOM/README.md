# VS SAD - Master IOM Module

## Overview
This module governs the creation, lifecycle management, and approval workflow for Inter-Office Memo (IOM) master data—specifically for promotional benefits such as Free Transfer of Rights (Alih Hak), Free AJB Costs, and Free IPL—within the VS SAD platform.

## Core Functions
* **Multi-Tier Approval Workflow:** Requires formal submission and approval processing before any newly created Master IOM transitions to an active status, moving away from immediate activation.
* **Lifecycle & Status Management:** Tracks records across distinct statuses including Draft (during initial creation, waiting, or rejection), Active (upon approval), and Inactive (manually or automatically expired).
* **Controlled Document Re-upload:** Permits continuous updates and re-uploading of IOM attachment files for approved records, backed by mandatory confirmation prompts and audit logging.
* **Automated Expiry & Manual Deactivation:** Supports setting specific end dates to automatically deactivate IOMs, or allows manual deactivation by specifying an expiry date.

## Summary of Changes (To-Be vs. As-Is)
* **Approval Integration:** Shifted from instant activation upon creation to a mandatory approval gate before a Master IOM becomes active.
* **Controlled Attachment Updates:** Restricted post-approval edits primarily to document attachments, ensuring strict change traceability through confirmation dialogs and history logs.
* **Automated Lifecycle Expiry:** Introduced structured expiration mechanisms to govern the active validity period of promotional IOM terms.

## Business Impact & Value
* **Enhanced Governance:** Prevents unverified promotional IOMs from being applied by enforcing mandatory review and approval cycles.
* **Strict Version Control:** Maintains clear audit trails of document modifications and approval histories, ensuring transparency between operational updates.
* **Automated Compliance:** Reduces administrative oversight by automatically retiring expired promotional terms based on defined end dates.
