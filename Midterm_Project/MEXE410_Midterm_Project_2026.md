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

Before this product can be sold legally, it must go through a **Conformity Assessment**. As defined in Module 2, this involves a set of processes to show that your product meets the requirements of a specific standard. 

To simulate this, the class will do **Cross-Auditing**. You will be directly defending your product in a debate against your own classmates, and you will be auditing their products in return. Every group will play two roles at the same time:
1. **The Innovators:** Defending your engineering choices against your classmates.
2. **The ISO Auditors:** Inspecting and challenging the safety and standards of *another* classmate's group.

*(Example: Group 1 debates Group 2. Group 2 debates Group 3. Group 3 debates Group 1.)*

---

## 🛠️ The 4-Phase Accreditation Process

### Phase 1: Product Development & Standards Mapping (Submission Deadline)
**Role:** The Innovators  
Invent a unique mechatronic product. You only need to write the engineering documents, which will be hosted on GitHub. 

1. **Repository Setup:** Create a GitHub repository for your group project. You must name it exactly as follows:
   `Midterm_MEXE410_Section_Group#_2026` *(Example: Midterm_MEXE410_3301_Group1_2026)*. 
2. **Collaborators:** Add the lecturer AND the members of your assigned Auditing Group as collaborators to this repository.
3. **The Technical Report:** Inside your repository's `README.md` file, write your report containing:
   * **Product Description:** What it does, who uses it, and its main parts.
   * **Safety Architecture:** Clearly explain the emergency stops, fail-safes, and physical limits. Remember the distinction from Module 2: codes set the minimum acceptable level of safety, while standards tell you "how to" execute them.
   * **Standards Mapping:** Name at least **two** specific standards from Module 2 that apply to your product, and explain exactly how your product follows them. You can use ISO 10218, NFPA codes, IEEE standards, or Philippine Electrical/Mechanical Codes.

### Phase 2: The Report Exchange & Internal Review
**Role:** The ISO Auditors  
Your group will be granted collaborator access to the Innovators' repository. 
* **The Mission:** Read their `README.md` carefully. As professional ISO Auditors, look for the physical safety gaps and logic errors your classmates missed.
* **The Deliverable (Keep it Secret & Print it!):** Write your **Audit Checklist**. This must include your 5 highly technical, difficult questions, **along with your expected answers or engineering notes** justifying why you are asking them. 
  * **Do NOT upload this to their repository yet.** If you upload it early, they will see your questions and prepare scripted answers. 
  * **You must bring a printed, physical copy** of this checklist (questions and expected answers) on Presentation Day to use during the live debate and to submit to the lecturer.

### Phase 3: The Live Defense and Classmate Debate (Presentation Date)
**Role:** Both Innovators and Auditors  
*(This is your live, face-to-face evaluation).*
* **The Pitch (5 mins):** The Innovators present the product from their `README.md` and explain their standards mapping.
* **The Debate (5-10 mins):** The assigned ISO Auditors take the floor. They will use their **printed physical checklist** to challenge and cross-examine the Innovators live. The Innovators must respond immediately to the questions and defend their engineering choices using facts and the standards outlined in Module 2. 

### Phase 4: Non-Conformance & CAPA Resolution
**Role:** Both Innovators and Auditors  
After the live debate concludes, all formal audit documents must be uploaded to the Innovators' repository for the lecturer to grade.
* **The Audit Trail (From Auditors):** The auditing group must now upload their `Phase2_Audit_Checklist.md` to the Innovators' repository to prove what they asked. Then, they must create a new file named `Phase4_NCR.md`. This is the formal Non-Conformance Report listing the major standards violations the Innovators failed to defend during the debate.
* **The CAPA (From Innovators):** The innovating group must review the NCR and create a final file named `Phase4_CAPA.md` (Corrective and Preventive Action). In this file, explain exactly how you will re-engineer your product to fix the mistakes your classmates listed in the NCR.

---

## 📊 Grading Rubric (100% Total)

**As Innovators (50%):**
* **Technical Report (20%):** Accuracy of standards used and details of the safety features.
* **Live Defense (15%):** Ability to professionally debate classmates, answer questions, and defend engineering choices.
* **CAPA Resolution (15%):** How realistic and compliant the proposed engineering fixes are.

**As ISO Auditors (50%):**
* **Audit Checklist (20%):** The technical difficulty and relevance of the 5 prepared questions.
* **The Debate (15%):** Professionalism, critical thinking, and the ability to spot and argue errors live against classmates.
* **The NCR (15%):** Accuracy in naming specific ISO/IEC standards when listing the product's violations.

---

## 📝 Example of Standards Mapping and Auditing (For your Repository)
*You can use this format in your Technical Reports and Audit Checklists.*

### 🛠️ Innovator's Standards Mapping Example
**Product:** Automated Welding Robot Cell
* **Mapped Standard 1: ISO 10218-1 (Industrial Robot Safety)**
  * *How we comply:* Our robot arm is programmed to have an inherent safe design by limiting its maximum joint speed to 250 mm/s when a human enters the collaborative workspace, reducing the risk of impact hazards.
* **Mapped Standard 2: Philippine Electrical Code**
  * *How we comply:* The entire power distribution system of the robot cell uses materials and wiring sizes that establish the basic standard for the safe use of electricity for power and heat.

### 🕵️ Auditor's Debate Question Example (Based on the mapping above)
* *"In your mapping, you stated that the robot slows down to 250 mm/s when a human enters the space to comply with ISO 10218-1. However, if the main sensor loses power, what is the mechanical fail-safe? Have you considered the risk of the sensor failing, and does that comply with the minimum acceptable level of safety outlined in Module 2?"*
