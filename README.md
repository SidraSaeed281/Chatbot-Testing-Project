# Samarco Motors Chatbot Evaluation

## 📌 Project Overview
This repository contains a **manual QA evaluation project** performed on the Samarco Motors customer chatbot.  
It demonstrates the ability to design, document, and organize **test cases, execution results, and bug reports** using industry‑standard QA documentation formats.

The goal of this project is to showcase QA practices for chatbot evaluation, covering:
- Functional accuracy  
- Conversation flow  
- Data validation  
- Usability  
- Defect tracking  

---

## 📊 Evaluation Scope
- **Total Test Cases:** 30  
- **Correct Responses:** 17  
- **Partially Correct:** 5  
- **Incorrect Responses:** 8  
- **Overall Accuracy:** 58% (87/150 points)

---

## 📂 Repository Structure
│
├── bug-test-sheet/          # Raw bug and test case documentation
│   └── Bug_Test_Sheet.xlsx
│
├── final-report/            # Final evaluation report
│   └── Samarco_Chatbot_Evaluation_Report.pdf
│
└── README.md

---

## 🧩 Key Findings

### ✅ Strengths
- Handles **basic queries and FAQs** effectively  
- Provides **structured responses** for services and recommendations  
- Good **fallback handling** for irrelevant questions  
- Guides users toward **test drives, booking, and contact options**

### ⚠️ Critical Issues
1. **Conversation Flow Breakdown** – chatbot gets stuck in loops, cannot handle intent changes  
2. **Data Accuracy Problems** – incorrect stock, pricing, outdated offers  
3. **Context Handling Errors** – misuses prior query context  
4. **Incorrect/Risky Information** – wrong roadside assistance number, missing warranty details  

---

## 🛠 Recommendations

### High Priority
- Improve **context handling** and session management  
- Enable **smooth flow switching** when user intent changes  
- Sync chatbot with **live website data**  
- Keep responses **concise and relevant**  
- Add **fallback options** for errors  

### Medium Priority
- Increase response precision  
- Reduce unnecessary content  
- Add smarter fallback prompts  

### Low Priority
- Enhance personalization  
- Improve tone and engagement  

---

## 📌 Final Conclusion
The chatbot demonstrates **basic functionality** but is **not reliable** for real-world customer interaction.  

- **Strength:** Basic query handling  
- **Weakness:** Flow, accuracy, and intelligence  
- **Overall Accuracy:** 58%  
- **Final Rating:** ⭐⭐⭐☆☆ (3/5)

---

## 🧪 Example Bug Report – Inventory Mismatch
**ID:** INV_BUG_002  
**Title:** Chatbot shows unavailable Audi Q8 as in stock  
**Severity:** High  
**Priority:** High  

**Steps to Reproduce**
1. Ask chatbot about Audi Q8 availability  
2. Chatbot responds “Available in stock”  
3. Verify against official Samarco Motors website  

**Expected Result**  
Chatbot should correctly indicate that Audi Q8 is **not available**.  

**Actual Result**  
Chatbot incorrectly shows Audi Q8 as available.  

---

## 🧪 Testing Types Performed
- **Functional Testing** → Verified chatbot flows (basic info, inventory, booking, contact)  
- **Usability Testing** → Ensured user‑friendly flows and fallback handling  
- **Positive & Negative Testing** → Covered both valid and invalid input scenarios  
