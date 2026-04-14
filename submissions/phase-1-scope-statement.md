# Phase 1 Project Scope: Foundations 🧱

## Table of Contents

1. [Included System Aspects & Capabilities](#1-included-system-aspects--capabilities)
2. [Exclusions](#2-exclusions)
3. [Assumptions](#3-assumptions)
4. [Dependencies and Constraints](#4-dependencies-and-constraints)
5. [Credibility](#5-credibility)

## 1. Included System Aspects & Capabilities

- **ID Verification:** Authentication portal form to upload documents for agent review
- **Customer Account Summaries:** A real-time view of balances and self-service options for the customer, including Promise-to-Pay (P2P) commitments and Speak to Agent (S2A) escalations (JTBD #11)
- **Hybrid Account History:** Real-time account data from the Legacy DB, spreadsheets and manual notes (scanned) for the agents (a key requirement from Gareth and the agents)
- **Automated P2P Follow-up and Next Action Reminders for Agents:** To recover lost revenue from missed or delayed follow-ups

## 2. Exclusions

- **Automated case complexity / risk tagging** — it's a complex job, and takes time to define automation routes for cases that often require human discernment and empathy
- **Full consolidation of data sources** — this will take a significant amount of time, money and effort
- **Integration with payment systems** — a great solution that requires some technical expertise, and for which we don't have the time to implement in Phase 1
- **Full data trails for auditing** — to do this well, it will take a lot of attention to detail (read: time)


## 3. Assumptions

For this Phase 1 scope to be successful, the following must hold true:

- **Data Accessibility:** The Legacy DB allows for straightforward data transfer and spreadsheet data is structured enough for a standardised CSV upload.
- **Stakeholder Alignment:** Operations teams will be satisfied with a "hybrid view" dashboard where agents cross-reference digital summaries with indexed PDFs rather than a fully unified database.


## 4. Dependencies and Constraints

- **Legacy Integration:** Access to the Legacy DB and the successful mapping of account fields to the new portal UI.
- **Compliance/Legal Sign-off:** Daniel Okoye's approval of the legal wording for digital P2P commitments.
- **Digitisation Bottlenecks:** The speed at which manual notes can be scanned and indexed determines the completeness of the hybrid history dashboard for agents.


## 5. Credibility

This scope directly targets the top-ranked opportunities from Week 1, beginning to recover the **15% revenue leak** and reducing the "wasted" agent time reported by seven key stakeholders. By prioritising Promise-to-Pay and Account Summaries, we deliver measurable financial value immediately to satisfy the Finance Director's demands.

From a feasibility standpoint, the method of using OCR-indexed PDFs avoids the high technical risk of a full data migration, making the delivery timeline realistic. This approach also manages change and adoption risk by giving agents the full interaction record they lack today, ensuring they have the confidence to transition to the new system without fear of losing historical records.
