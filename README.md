# HugoLandingPages
Using Hugo for landing pages and portfolio case studies.

## 1. Primary Directive

This website's sole purpose is to serve as an automated engine for attracting, qualifying, and converting high-value opportunities across three core verticals: **UX/Product Leadership**, **Technical Consulting**, and **SMB Acquisition**. Every component must serve this directive.

## 2. Strategic Architecture: The Triage Funnel

The website is not a portfolio; it is a system designed to sort visitors into specific, high-intent funnels.

-   **`/home` (The Triage Hub):** The central hub has one job: categorize a visitor and route them to the appropriate landing page with zero friction. The messaging is built around solving systemic problems, immediately filtering for prospects with the right mindset.
-   **The Three Funnels:** Each subsequent landing page is a specialized environment engineered to speak the language of a specific target persona, address their core pain points, and guide them toward a predefined monetization "play."

## 3. The Playbooks

Each funnel is a self-contained playbook with a defined target, a core problem to exploit, and a clear path to revenue.

### Playbook #1: The UX & Product Systems Funnel (`/ux`)

* **Target Persona: The Scaler** (Hiring Managers, VPs of Product/UX, Founders). They are trying to build or fix a product development team and are frustrated by slow processes, inconsistent output, and a lack of strategic leadership.
* **Identified Pain:** Their current design/product function is a bottleneck. They are losing money and market share due to poor user experience, inefficient workflows (DesignOps), or an inability to hire and retain senior talent.
* **The Pitch:** Position yourself as a systems-thinker who doesn't just design screens but architects scalable product development ecosystems. The messaging focuses on building efficient teams, implementing robust processes, and delivering quantifiable business outcomes. The portfolio exists as *evidence* of this capability, not just a gallery of work.
* **Entry Points & Offers:**
    * **Lead Magnet (for HR/Recruiters): The "No-Fluff UX Staffing Guide."** A downloadable PDF that demystifies UX roles and evaluation criteria. It provides immediate value, establishes your authority, and subtly frames you as the ideal candidate and a potential staffing consultant.
    * **Lead Magnet (for Managers/Leaders): The "UX Maturity Audit."** An automated quiz that allows a leader to benchmark their organization's UX capabilities. It captures a high-intent lead and provides you with critical intelligence on their internal weaknesses, creating a perfect entry point for a consulting conversation.
    * **Core Offer: The "Rapid MVP Workshop."** A high-value, fixed-scope design sprint to quickly validate and prototype new product concepts.
* **Monetization Plays:**
    1.  **Fractional UX Leadership:** High-margin monthly retainers.
    2.  **DesignOps "Rescue" Sprint:** A high-ticket, fixed-scope project.
    3.  **Strategic Full-Time Role:** Filter for high-leverage, remote-first leadership positions.

### Playbook #2: The Technical Operations Funnel (`/tech-ops`)

* **Target Persona: The Technical Leader** (CTOs, VPs of Engineering, Lead Architects). They are technically proficient but lack the bandwidth to solve nagging operational inefficiencies within their development pipelines, internal tooling, or automation strategies.
* **Identified Pain:** Their team is losing valuable engineering hours to manual, repetitive tasks. Their CI/CD pipeline is brittle, their internal systems don't communicate, and they need expert-level, hype-free solutions.
* **The Pitch:** Speak to them as a peer. The language is direct, technical, and ROI-focused. The value proposition is simple: "I eliminate the operational drag that is costing your most expensive employees their time."
* **Entry Points & Offers:**
    * **Core Offer: The "Technical Operations Diagnostic."** A one-week deep-dive engagement. Through observation and interviews, you identify the primary sources of friction and deliver a concrete, actionable proposal to solve them. This is a paid discovery project.
    * **Core Offer: The "Rapid MVP Workshop."** Positioned here as a way to quickly build and validate internal tooling and proof-of-concepts.
* **Monetization Plays:**
    1.  **Workflow Automation Audit:** A paid diagnostic to map high-impact automation opportunities.
    2.  **Expert Consulting Retainer:** A block of hours per month for ongoing advisory.
    3.  **Project-Based Implementation:** Scoped projects to build specific internal tools.

### Playbook #3: The Business Systems & Acquisition Funnel (`/business-systems`)

* **Target Persona: The Bottlenecked Owner** (Aging or overwhelmed SMB owner-operators). Their business is successful but entirely dependent on their personal involvement. They are trapped and have no clear exit path.
* **Identified Pain:** They are the primary bottleneck for every decision and process. They cannot take a vacation without the business grinding to a halt. They want freedom but don't know how to achieve it.
* **The Pitch:** The messaging is 100% non-technical and empathetic. It focuses on tangible outcomes: "owner-free workflows," "getting your time back," and "building a business that runs without you." We are selling freedom, not software.
* **Entry Points & Offers:**
    * **Lead Magnet: The "Quiet Audit."** A low-friction entry point (e.g., a simple checklist or diagnostic call) to identify their single biggest operational pain point. This builds trust and grants access.
    * **Core Offer: The "Freedom Audit."** A one-week, on-site engagement where you shadow the owner, interview key staff, and map the core business operations. The deliverable is a roadmap to making the owner obsolete. This is a paid discovery project that serves as reconnaissance for the acquisition play.
* **Monetization Plays (Sequential):**
    1.  **Systemization Projects:** Implement automation and streamlined processes on a project or retainer basis.
    2.  **The Acquisition Offer:** Once you are embedded and have proven your value, propose a seller-financed acquisition. This is the ultimate leverage play.


## 4. Operational Principles

* **Technology Stack:** Hugo is used for speed, security, and zero maintenance. Cloudflare/GitHub Pages for free, automated hosting. We invest time in generating revenue, not managing infrastructure.
* **Content Strategy:** All content serves the playbooks. Case studies are framed as business cases with quantified ROI. Blog posts are written to attract our target personas by solving their specific problems.
* **Mindset:** This is not a resume. It is a machine.

## 5. Implementation Plan: The Component Maps

This project prioritizes speed and leverage. We use the pre-built components from the Hugoplate theme to assemble pages quickly, focusing effort on high-impact copy rather than custom development.

The `_planning/` directory contains the tactical build plan for the website. It is not part of the final deployed site. Its purpose is to translate the strategy outlined in this charter into a concrete assembly guide.

-   **`_planning/_component-inventory.md`**: A list of all available, pre-styled components in the Hugoplate theme. This is our "parts list." Before building, we identify the tools we have.
-   **`_planning/home.md`**: The component map and content plan for the main Triage Hub page.
-   **`_planning/ux.md`**: The component map and content plan for the UX & Product Systems funnel.
-   **`_planning/techOps.md`**: The component map and content plan for the Technical Operations funnel.
-   **`_planning/bizSystems.md`**: The component map and content plan for the Business Systems & Acquisition funnel.

Each file maps out the top-to-bottom sequence of components needed to construct the page, along with the core messaging and offers for each block. This ensures a rapid, strategy-aligned build.