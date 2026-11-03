# VS SAD - Perubahan Urutan Nama

## Overview
This module is a functional enhancement for the VS SAD (Vertical Solution - Sales Administration) platform, designed to standardize and govern consumer name sequencing, tax composition, and document validation across reservation and edit workflows.

## Core Functions
* **Real-Time Label Synchronization:** Automatically updates consumer tab labels dynamically as names are entered into the input fields.
* **Drag-and-Drop Sequence Management:** Implements a vertical drag-and-drop mechanism for consumer ordering to establish consistent user muscle memory and mitigate human error.
* **Attribute Consolidation Panel:** Unifies tax reporting percentages, unit ownership statuses, and FPU representative selections into a single integrated panel.
* **Dual-Container Interface:** Utilizes a side-by-side table layout within the edit menu to map original data against new sequences, supported by an auto-fill helper function.
* **Real-Time Document Preview:** Renders instant live previews of legal documents to enable immediate visual validation prior to data finalization.

## Summary of Changes (To-Be vs. As-Is)
* **Reservation Workflow:** Replaced horizontal tab navigation with vertical drag-and-drop ordering, consolidated fragmented tax and ownership inputs, and introduced real-time name tab synchronization alongside live document previews.
* **Edit Data Workflow:** Upgraded basic text-based sequence changes to a structured dual-container (side-by-side) interface and integrated live document previews prior to saving.
* **Approval Integration:** Connected consumer sequence modifications to a formal supervisor/manager approval workflow requiring change notes and the attachment of a consumer statement letter.

## Business Impact & Value
* **Standardization & Muscle Memory:** Eliminates inconsistent user experiences across reservation and edit menus, establishing a uniform operational workflow that minimizes errors.
* **Operational Efficiency & Validation:** Reduces verification friction by enabling instant visual confirmation through live document previews and unified input structures.
* **Administrative Governance & Compliance:** Strengthens internal controls by enforcing strict data validation rules (such as a mandatory exact 100% tax allocation and required ownership flags) and implementing formal management approvals for post-reservation edits.
