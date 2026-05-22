# IT Security Risk & Controls Audit – MedTech Industries Case Study

## Project Overview
[cite_start]This project simulates an external IT General Controls (ITGCs) audit and risk assessment based on the operational workflows of **MedTech Industries**[cite: 2]. The objective was to evaluate the effectiveness of the organization's control environment, identify operational and compliance gaps, and provide actionable remediation strategies aligned with industry risk management frameworks.

## Scope of Audit
The assessment focused on critical compliance and governance areas within the enterprise IT infrastructure, specifically targeting:
* [cite_start]**Change Management:** Reviewing emergency change procedures and standard approval workflows[cite: 5, 7].
* [cite_start]**Identity & Access Management (IAM):** Evaluating segregation of duties (SoD) and access control profiles[cite: 6].
* [cite_start]**System Development Lifecycle (SDLC):** Testing design effectiveness and pre-production validation processes for core systems (e.g., Payroll System)[cite: 12, 14].

---

## Key Findings & Deficiencies Identified

### 1. Change Management Bypass (Control Failure)
* [cite_start]**Issue:** A sampled emergency change did not adhere to the standard authorized approval process[cite: 7]. 
* [cite_start]**Impact:** The IT Director and the Change Advisory Board (CAB) failed to provide formal approval within the mandatory five-day post-implementation window[cite: 8]. This increases the risk of unauthorized or malicious code entering the production environment.

### 2. Segregation of Duties (SoD) Conflict
* [cite_start]**Issue:** A developer was found to have active access to the `CorpLawImp` role[cite: 4, 9].
* [cite_start]**Impact:** This created a critical SoD conflict by allowing a single individual to both develop and implement changes within the change management ecosystem, violating least-privilege principles[cite: 6, 9].

### 3. SDLC Design Review Gap
* [cite_start]**Issue:** Design reviews were completely omitted before migrating systems into active operation within the Payroll System SDLC[cite: 12, 14].
* [cite_start]**Impact:** Deploying systems without pre-production validation risks introducing severe vulnerabilities and failing to meet user or security specifications[cite: 14, 15].

---

## Proposed Remediation & Strategic Recommendations

Based on the audit findings, the following control enhancements are recommended to mitigate organizational risk:

* [cite_start]**Automated Change Monitoring:** Implement a weekly review cadence of all implemented emergency changes to systematically validate that proper CAB and management approvals were secured post-incident[cite: 10].
* [cite_start]**Access Governance Reviews:** Establish periodic access reviews targeting developer and implementer groups to ensure strict logical separation, preventing users from holding mutual membership in conflicting groups[cite: 11].
* [cite_start]**Mandatory Gatekeeping in SDLC:** Enforce mandatory, documented design reviews as a hard gate before any system or product is placed into active operations[cite: 15].

---

## Skills Demonstrated
* IT General Controls (ITGC) Testing
* Risk Assessment & Mitigation Strategy
* Governance, Risk, and Compliance (GRC) Principles
* Access Control & Segregation of Duties (SoD) Auditing
* Technical Writing & Executive Reporting
