# Midterm Project: Mechatronics Innovation & ISO/IEC Accreditation Simulation

**Institution:** Batangas State University – The National Engineering University  
**Course:** MEXE 410: Codes, Standards, and Professional Ethics for MExE  
**Target:** 3rd Year BS Mechatronics Engineering  

---

## 📅 Critical Schedules

Your deadlines depend strictly on your section. All submissions are due by **5:00 PM** on the dates below.

| Section | Groups | Project Creation & Submission Deadline | Live Presentation Date |
| :--- | :--- | :--- | :--- |
| **MEXE-3301** | 10 | July 5, 2026 (5:00 PM) | July 16, 2026 |
| **MEXE-3302** | 12 | July 4, 2026 (5:00 PM) | July 16, 2026 |
| **MEXE-3303** | 12 | July 4-5, 2026 (Submit: July 5, 5:00 PM) | July 11, 2026 (5:00 PM, Face-to-Face) |

---

## 📌 The Scenario
You are the lead engineering team at a Mechatronics startup. Your group has designed a new mechatronic product or service. 

Before this product can be sold legally, it must go through a **Conformity Assessment**. As defined in Module 2, this involves a set of processes to show that your product meets the requirements of a specific standard[cite: 1]. 

To simulate this, the class will do **Cross-Auditing**. You will be directly defending your product in a debate against your own classmates, and you will be auditing their products in return. Every group will play two roles at the same time:
1. **The Innovators:** Defending your engineering choices against your classmates.
2. **The ISO Auditors:** Inspecting and challenging the safety and standards of *another* classmate's group.

*(Example: Group 1 debates Group 2. Group 2 debates Group 3. Group 3 debates Group 1.)*

---

## 🛠️ The 4-Phase Accreditation Process

### Phase 1: Product Development & Standards Mapping (Submission Deadline)
**Role:** The Innovators  
Invent a unique mechatronic product. You only need to write the engineering documents. Submit a **Technical Report** containing:
* **Product Description:** What it does, who uses it, and its main parts.
* **Safety Architecture:** Clearly explain the emergency stops, fail-safes, and physical limits. Remember the distinction from Module 2: codes set the minimum acceptable level of safety, while standards tell you "how to" execute them[cite: 1].
* **Standards Mapping:** Name at least **two** specific standards from Module 2 that apply to your product, and explain exactly how your product follows them. You can use:
  * **ISO 10218-1:** For the inherent safe design of an industrial robot[cite: 1].
  * **ISO 10218-2:** For the safety of the robot system and cell integration[cite: 1].
  * **NFPA 70 or 70E:** For electrical safety[cite: 1].
  * **IEEE Standards:** Such as IEEE 802.11 for Wi-Fi interoperability[cite: 1].
  * **Philippine Electrical/Mechanical Codes**[cite: 1].

### Phase 2: The Report Exchange & Internal Review
**Role:** The ISO Auditors  
The lecturer will swap the reports. Your group will receive the Technical Report from another group of classmates.
* **The Mission:** Read their document carefully. As professional ISO Auditors, look for the physical safety gaps and logic errors your classmates missed.
* **The Deliverable:** Write an **Audit Checklist**. This is a list of 5 highly technical, difficult questions you will ask them during the live debate.

### Phase 3: The Live Defense and Classmate Debate (Presentation Date)
**Role:** Both Innovators and Auditors  
* **The Pitch (5 mins):** The Innovators present their product and explain their standards mapping.
* **The Debate (5-10 mins):** The assigned ISO Auditors (your classmates) take the floor. They use their 5 prepared questions to challenge the Innovators live. The Innovators must defend their engineering choices using facts and the standards outlined in Module 2. 

### Phase 4: Non-Conformance & CAPA Resolution
**Role:** Both Innovators and Auditors  
* **The NCR (From Auditors):** The auditing group writes a formal **Non-Conformance Report (NCR)** listing the major standards violations found during the debate.
* **The CAPA (From Innovators):** The innovating group must write a **Corrective and Preventive Action (CAPA)** plan. Explain exactly how you will re-engineer your product to fix the mistakes your classmates listed in the NCR.

---

## 📝 Example of Standards Mapping and Auditing (For your Repository)
*You can use this format in your Technical Reports and Audit Checklists.*

### 🛠️ Innovator's Standards Mapping Example
**Product:** Automated Welding Robot Cell
* **Mapped Standard 1: ISO 10218-1 (Industrial Robot Safety)**
  * *How we comply:* Our robot arm is programmed to have an inherent safe design by limiting its maximum joint speed to 250 mm/s when a human enters the collaborative workspace, reducing the risk of impact hazards[cite: 1].
* **Mapped Standard 2: Philippine Electrical Code**
  * *How we comply:* The entire power distribution system of the robot cell uses materials and wiring sizes that establish the basic standard for the safe use of electricity for power and heat[cite: 1].

### 🕵️ Auditor's Debate Question Example (Based on the mapping above)
* *"In your mapping, you stated that the robot slows down to 250 mm/s when a human enters the space to comply with ISO 10218-1[cite: 1]. However, if the main sensor loses power, what is the mechanical fail-safe? Have you considered the risk of the sensor failing, and does that comply with the minimum acceptable level of safety outlined in Module 2?"*
