# Internship README — AI-Powered Client Query Automation & Document Classification Tool

## 👤 Intern Details
- **Name:** Harsh Raj
- **Roll No.:** 2410030410
- **Program:** B.Tech CSE, IILM University, Greater Noida, U.P.
- **Batch:** 2026-27 (5th Semester)
- **Contact:** harshrajj.work@gmail.com

## 🏢 Company / Organisation
- **Company:** J. D. Jones & Co. (P) Ltd.
- **CIN:** U10200WB1923PTC004802
- **Registered Office:** 9B Dr. Martin Luther King Sarani (Wood Street), 2nd Floor, Kolkata – 700016, India
- **Industry:** Shipping, Trading & Allied Business Services
- **Certification:** ISO 9001:2015 (DNV·GL Certified)
- **Contact:** Phone 91 33 4050 1000 · Fax 91 33 4050 1075 · Email comments@jdjones.com · Web www.jdjones.com

## 📌 Internship Terms
- **Position:** Intern – AI Developer
- **Offer Date:** 31st July 2026
- **Duration:** 6th August 2026 – 5th November 2026 (3 months)
- **Work Timings:** 10:00 AM – 6:30 PM (Mon–Fri), 10:00 AM – 2:30 PM (Sat)
- **Leave Policy:** No paid leave except Sundays & Company Holidays
- **Reporting To:** Senior as designated by Management / AI Development team
- **Confidentiality Clause:** No direct soliciting of business with clients introduced by the company; all client interaction must go through the company
- **Termination Conditions:** Immediate termination for 10+ continuous days' absence, false credentials, or misconduct/insubordination/incompetence

## 🎯 Project Overview
**Title:** Development of an AI-Powered Client Query Automation & Document Classification Tool

**Problem Statement:** The operations team receives a high volume of routine client queries daily (shipment status, documentation, billing) that are read and answered manually — repetitive and time-consuming, especially for predictable, recurring categories.

### Objectives
- Gain hands-on, industry-level experience applying AI/NLP to a real business problem
- Design a prototype that classifies incoming client queries by category
- Build a module suggesting draft responses for common queries
- Develop a basic document-tagging utility
- Learn professional development practices, version control, and team collaboration

### Scope
- ✅ In scope: prototype on sample/anonymised data, accuracy & F1 measurement, response-suggestion aid, document tagging, time-saving estimation
- ❌ Out of scope: production deployment, live client-channel integration, fully automated reply sending

## 🛠️ Technologies & Tools
| Category | Tools |
|---|---|
| Language | Python 3 |
| NLP | NLTK / spaCy, scikit-learn |
| Data Handling | Pandas, NumPy |
| Modelling | TF-IDF + Logistic Regression |
| Interface | Flask (internal dashboard) |
| Version Control | Git & GitHub |
| Dev Environment | VS Code, Jupyter Notebook |
| Tracking | Excel, Google Sheets |

## 🏗️ System Architecture
1. **Text Pre-processing & Classification Pipeline** — clean → tokenise → TF-IDF → Logistic Regression → predicts 1 of 5 categories
2. **Response-Suggestion Engine** — retrieves closest-matching template reply for staff review/edit
3. **Document-Tagging Utility** — keyword/pattern matching tags incoming documents (invoice, shipping bill, client letter, etc.)

All three modules are exposed via a lightweight internal **Flask dashboard**.

## 🧪 Methodology
1. **Requirement Understanding** — shadowed operations team, identified frequent query categories
2. **Data Collection & Preparation** — sample anonymised dataset tagged across 5 categories; tokenisation, stop-word removal, TF-IDF
3. **Model Development** — compared Logistic Regression, Naive Bayes, SVM; selected TF-IDF + Logistic Regression
4. **Response-Suggestion Module** — rule-assisted template retrieval, human-reviewed
5. **Document Tagging Utility** — keyword/pattern-based tagging
6. **Testing & Internal Demo** — Flask dashboard tested by AI Development team; iterative feedback incorporated

### Query Categories
- Shipment Status
- Documentation Request
- Billing Query
- General Enquiry
- Complaint / Escalation

## 📊 Results
- **Overall Accuracy:** 93.8%
- **Weighted F1-Score:** 0.94
- **Estimated Drafting Time Saved:** ~40–50%

| Category | Precision | Recall | F1-score |
|---|---|---|---|
| Billing Query | 1.00 | 1.00 | 1.00 |
| Complaint / Escalation | 0.83 | 1.00 | 0.91 |
| Documentation Request | 0.87 | 0.93 | 0.90 |
| General Enquiry | 1.00 | 1.00 | 1.00 |
| Shipment Status | 1.00 | 0.81 | 0.90 |

**Key Observation:** Most confusion occurred between "Shipment Status" and "Documentation Request," since delay-related queries often also referenced missing documents.

## ✅ Expected Outcomes
- Working prototype classifying client queries with ~94% test accuracy
- Reduced manual effort in drafting responses to repetitive queries
- Basic document-tagging utility for faster sorting
- Demonstrated feasibility for scaling into a production tool (with a larger training dataset)
- Personal growth in Python, NLP, scikit-learn, Flask, time management, teamwork, and presenting technical work to non-technical stakeholders

## 📎 Supporting Documents
- **Offer Letter:** Issued 31st July 2026, signed by Director, J. D. Jones & Co. Pvt Ltd
- **Completion Certificate:** ⏳ Pending — to be requested from the company and attached before final report submission

## 📚 References
1. J. D. Jones & Co. (P) Ltd. — Company records and internal documentation, 2026
2. Scikit-learn Documentation — https://scikit-learn.org/
3. NLTK Documentation — https://www.nltk.org/
4. Flask Documentation — https://flask.palletsprojects.com/
5. Pandas Documentation — https://pandas.pydata.org/docs/
