# 🚨 Mechatronics QA Engineering Audit (15% Final Grade)

**Institution:** Batangas State University – The National Engineering University  
**Module:** Industrial Robotics & International Compliance Standards (ISO/IEC)  

## 📌 The Scenario
In global heavy industry, mechatronics engineers frequently work with international teams. A critical part of Quality Assurance (QA) is verifying technical documentation. An automated system is only as safe as its manual. 

Your engineering firm has received translated operation manuals from 12 international subsidiaries. However, an internal audit suspects that **one lethal engineering logic error** has been mistranslated or altered in each document. 

Adhering to strict, zero-tolerance industrial safety standards (aligned with German Engineering frameworks), your group must identify and correct the hazard before the machinery is deployed. Failure to do so will result in catastrophic mechanical failure, facility destruction, or loss of life.

## 🛠️ Your Mission
You will be assigned one foreign-language engineering excerpt corresponding to a specific industrial sector (e.g., Heavy Manufacturing, Medical Robotics, Petrochemical). 

You are strictly prohibited from using basic translation tools to blindly "guess" the error. You must conduct a professional engineering audit using a Hybrid AI Approach.

### ⚙️ The Audit Workflow:
1. **The Baseline Translation:** Run your assigned foreign text through DeepL (or Google Translate for unsupported languages like Urdu, Tagalog, or Arabic) to obtain a raw, literal English baseline.
2. **AI Contextual Analysis:** Paste your baseline translation into a Large Language Model (e.g., ChatGPT, Claude 3.5 Sonnet, or Gemini). 
3. **The Interrogation:** Prompt the AI as a QA Engineer. *(Example: "Act as a Mechatronics QA Auditor. Analyze this translated procedure. Does this mechanical logic make safe, physical sense according to ISO standards? Flag any relay states, kinematic bounds, or thermal limits that could cause a catastrophic failure.")*
4. **The Isolation:** Identify the exact logic error. 

## 📝 Deliverables & Submission
Your group must submit a formal QA Audit Report via a **Pull Request** to this repository (or your designated submission portal) containing:

* **Group Number & Sector:** (e.g., Group 1: Heavy Manufacturing)
* **Target Language:**
* **The Raw Translation:** (The direct English output from DeepL/Google).
* **The Fatal Flaw:** (Identify the exact sabotaged term, e.g., "normally open" vs "normally closed").
* **The Engineering Consequence:** (A brief, highly technical explanation of exactly *why* this error would cause a physical catastrophe on the factory floor).
* **The Corrected Code/Text:** (The repaired sentence demonstrating proper compliance).

> **⚠️ WARNING:** Do not simply look for an "extra zero" in the numbers. The sabotage is embedded in the **engineering logic** (e.g., sensor configurations, valve states, material properties). You must understand the physics of the entire paragraph to pass this audit.
