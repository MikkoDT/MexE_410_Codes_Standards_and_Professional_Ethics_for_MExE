# 🚨 Application Activity 1: Mechatronics QA Engineering Audit (15% Final Grade)

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

---

## 💻 GitHub Submission Instructions
Your group must submit a formal QA Audit Report via a **Pull Request (PR)** to this repository. Follow these strict version control procedures:

### Step 1: Fork and Clone
1. **Fork** this repository to your group leader's GitHub account.
2. **Clone** the forked repository to your local machine.

### Step 2: Create a Branch
Create a new branch for your group's audit using the following naming convention *(replace XX with your group number)*:  
```bash
git checkout -b audit-group-XX
