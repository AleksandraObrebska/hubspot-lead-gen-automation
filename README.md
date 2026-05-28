# HubSpot CRM: Automated Lead Generation & Data Segmentation Architecture

## 📌 Project Overview
This project demonstrates the design and implementation of an end-to-end automated marketing and operations workflow within HubSpot CRM. It replaces manual lead tracking with an intelligent, data-driven system that delivers assets, tracks customer behavior, and automatically segments users based on engagement.

### Key Capabilities Demonstrated:
*   **CRM Architecture:** Managing lead lifecycles and pipeline automation.
*   **Advanced Branching Logic:** Creating conditional customer journeys based on behavioral data.
*   **Data-Driven Operations:** Setting up real-time analytics dashboards for stakeholders.

---

## ❌ The Business Problem (Context)
In standard email marketing setups, systems often treat contacts as static list entries rather than dynamic CRM profiles. This creates severe operational bottlenecks:
*   No clear visibility into individual contact engagement journeys.
*   Manual verification of email clicks and data entry to update lead statuses.
*   High risk of human error and lost conversion opportunities due to lack of automated follow-ups.

---

## ⚙️ The Solution & Implementation

I architected and deployed a 4-stage automated solution within HubSpot:

1.  **Data Capture:** Configured a high-converting form to capture user data and profile business challenges.
2.  **Behavioral Workflow (If/Then Branching):** Designed a conditional sequence that triggers instantly upon form submission:
    *   **Path A (Engaged):** If the contact clicks the asset download link, the system automatically updates their property to **Marketing Qualified Lead (MQL)**, signaling readiness for the sales team.
    *   **Path B (Nurturing):** If the contact does not interact within 2 days, a personalized **Follow-up email** is automatically triggered to recover the conversion.
3.  **Communication Personalization:** Implemented dynamic personalization tokens (`First Name`) with strict `Fallback values` ("there") to ensure seamless, professional outreach.
4.  **Analytics & Performance Dashboard:** Built a live dashboard to monitor campaign performance, lead flow, and email deliverability in real time.

---

## 📈 Visual Documentation (Architecture & Reports)

### 1. Workflow Automation Setup
The fully active workflow demonstrating the automation trigger, delay, and advanced branching logic:

![Workflow Part 1](images/workflow-part1.png)
![Workflow Part 2](images/workflow-part2.png)
![Workflow Part 3](images/workflow-part3.png)

### 2. Campaign Performance Dashboard
The real-time analytics hub tracking total leads generated, conversion stages, and automated email engagement metrics:

![HubSpot Analytics Dashboard](images/dashboard.png)

---

## 📊 Business Impact & Key Metrics
*   **0% Manual Labor:** The entire delivery, follow-up, and CRM segmentation process is 100% automated.
*   **Data Enrichment:** Sales teams receive enriched CRM contact cards with exact timeline behavior before scheduling discovery calls.
*   **Recovered Conversions:** Automated behavioral branching ensures unengaged leads receive an optimized second touchpoint without manual supervision.

---

## 🛠️ Tech Stack & Skills Applied
*   HubSpot CRM
*   HubSpot Marketing Automation (Workflows)
*   HubSpot Reporting & Analytics Dashboards
*   Process Mapping & Operations (PMO)
