# IS 3060 KPMG Consulting Challenge — Track A: Digital Transformation

**Client:** Wasatch Outfitters Collective (WOC)  
**Consulting Track:** Track A — Digital Transformation  
**Course:** IS 3060 (David Eccles School of Business, University of Utah)
---
## About the Consulting Team

We are a student consulting team in **IS 3060** at the **University of Utah's David Eccles School of Business**, partnering on the **KPMG-Sponsored IS Consulting Challenge** for **Track A: Digital Transformation** (`Wasatch Outfitters Collective`).

- **Jackson Palmer**
- **Bessie Ibanez**
- **Samuel Meyers**
- **Landon Peartree**

Together, we examine WOC's disconnected rental spreadsheets, unlinked repair logs, and cross-store coordination gaps across **Downtown SLC**, **Sandy**, and **Park City** to recommend a practical, staged 6–12 month digital solution backed by progressive lab evidence.

---

## Executive Problem Statement

Wasatch Outfitters Collective (WOC) is a growing outdoor recreation and retail business operating three store locations (**Downtown SLC**, **Sandy**, and **Park City**) with offerings spanning retail gear sales, equipment rentals, repair services, guided outdoor experiences, and corporate team events. As demand has grown, WOC's internal operational workflows have remained fragmented:

- **Disconnected Rental Tracking:** Each store manages rentals in separate Google Sheets, forcing staff to manually check availability across locations and call other stores to confirm inventory.
- **Unlinked Repair Workflows:** Repair activities are tracked separately using paper tags and a standalone repair log, creating conflicting status records and risking damaged gear being reserved or rented out.
- **Limited Managerial Visibility:** Managers lack unified, real-time visibility into utilization, repair bottlenecks, and cross-location inventory to support purchasing, maintenance scheduling, and customer service.

**Consulting Objective:** Recommend and prototype a practical, affordable, and staged digital transformation (6–12 month horizon) tailored to a mid-sized organization with limited IT staff—integrating people, processes, and technology across store associates, repair technicians, store managers, and customers.

---

## Repository Structure & Lab Artifacts

All artifacts are organized under `IS3060 - KPMG - TrackA/`:

### 1. Business Intelligence & Problem Definition - milestone-01 (`lab2-tableau/`)
Analyzes rental and repair operations data (`woc_track_a_rentals.csv`) to identify operational bottlenecks, inventory/repair visibility gaps, and utilization patterns.
- `Part2_WOC_Dashboard.twb` — Tableau workbook containing WOC rental/operations visualizations.
- `Tableu Reflection & Memo.docx` — Consulting memo and analytical reflection on findings from the WOC dataset.
- `Tableu1.png` – `Tableu5.png` — Exported dashboard and worksheet screenshots illustrating key metrics and findings.

### 2. User Experience Prototype - milestone-02 (`Lab3-mobile-app/`)
Demonstrates a mobile/user-facing interface prototype and workflow design for interacting with equipment/rental processes.
- `User_Page1.png` through `User_Page3.png` — User interface screens from the mobile prototype.
- `Code_Page1.png` through `Code_Page3.png` — Underlying build/logic/code views supporting the prototype.
- `Lab 3 Reflection ^0 Consulting (1).pdf` — Reflection and consulting notes connecting the UX prototype to WOC's operational needs.

### 3. Process & Web Application Prototype - milestone-03 (`lab7-web-app/`)
Iterates on a web-based prototype across multiple versions to support a more unified digital workflow.
- `index_v1.html.html`, `index_v2.html.html`, `index_v3.html.html` — Iterative versions of the web application prototype.
- `web_screenshot_1.png` through `web_screenshot_4.png` — Screenshots capturing the web prototype interface and features.
- `Lab7_Web_Evidence.pdf` — Documentation/evidence summarizing the web prototype build and functionality.

### 4. AI-Enabled Customer Engagement Prototype - milestone-04 (`lab8-ai-social-media-assistant/`)
Explores AI-assisted customer communication/engagement to help address multi-channel inquiries and responsiveness.
- `Lab8_AI_Social_Media_Assistant_Evidence.pdf` — Evidence and documentation for the AI social media assistant prototype.

### 5. AI Opportunity Evaluation & Outsourcing - milestone-05 (`lab10-ai-outsourcing/`)
Evaluates AI models, external/outsourced options, and strategic/executive considerations for responsible AI adoption and implementation.
- `Lab_10_Decathlon_AI_Executive_Proposal (1).docx` — Executive proposal document evaluating AI/outsourcing options and recommendations.
- `Teach_Machine_AI_model.png` — Teachable Machine AI model setup/training visual evidence.
- `AI_model_Test_01.png`, `AI_model_Test_02.png` — Test results and evaluation screenshots for the AI model.
- `outsource_candidate_01.png` – `outsource_candidate_03.png` — Candidate evaluation screenshots/evidence for outsourcing/solution options.

### Final Consulting Recommendation (`WOC_TrackA_Final_Recommendation.pdf`)

* **File Description:** Executive consulting brief synthesizing our team's end-to-end Track A (Digital Transformation) solution for Wasatch Outfitters Collective. It connects our semester dependency chain—from multi-store Tableau utilization analysis (`lab2-tableau`) and interactive rental/repair prototypes (`Lab3-mobile-app`, `lab7-web-app`) to AI support evaluation (`lab8`, `lab10`)—into a practical, three-phase **6–12 month implementation roadmap**.
* **Summary of Recommendation:**
  * **Phase 1 (Months 1–3) — Centralized Rental & Repair Hub:** Consolidate Downtown SLC, Sandy, and Park City onto a single cloud rental and repair platform with automated repair status locks to eliminate double-bookings and damaged-gear checkouts.
  * **Phase 2 (Months 4–6) — Real-Time Managerial BI:** Connect unified operational data into standardized Tableau dashboards for cross-store inventory visibility, utilization tracking, and repair turnaround monitoring.
  * **Phase 3 (Months 7–12) — AI Support Triage & Access Governance:** Roll out human-supervised AI assistance for routine customer inquiries alongside Role-Based Access Control (RBAC) and automated seasonal employee offboarding.

---

## Deliverable Notes

- **Audit Trail:** Artifacts are maintained progressively in this repository to support our final consulting recommendation.
- **Executive Presentation:** A 10-minute (~10–12 slide) narrated presentation drawing directly from the committed lab artifacts above, including prototype walkthroughs and a practical 6–12 month rollout/change management plan for WOC.
