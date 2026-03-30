# 🔐 API Security Risk Analysis

## 📌 Project Overview
This project is part of the Cyber Security Internship (Future Interns 2026).

The objective of this project is to analyze a public API and identify common security risks such as:
- Missing authentication
- Broken authorization
- Excessive data exposure
- No rate limiting
- Input validation issues

---

## 🧪 API Tested
- JSONPlaceholder (Public Test API)

---

## 🛠️ Tools Used
- Postman (API testing)
- Browser DevTools (optional)

---

## 🔍 Methodology
The following steps were performed:

1. Selected a public API
2. Reviewed API endpoints
3. Tested endpoints using Postman
4. Inspected responses and headers
5. Identified security risks
6. Classified risk severity
7. Suggested remediation steps

---

## 🚨 Key Findings

- ❌ No Authentication → Anyone can access the API  
- ❌ Broken Authorization → Access to other users' data  
- ❌ Excessive Data Exposure → Sensitive data visible  
- ❌ No Rate Limiting → Unlimited requests allowed  
- ❌ Input Validation Issues → Invalid inputs accepted  

---

## ⚠️ Risk Summary

| Vulnerability | Severity |
|--------------|---------|
| Missing Authentication | High |
| Broken Authorization | High |
| Data Exposure | Medium |
| No Rate Limiting | Medium |
| Input Validation | Low |

---

## 🛡️ Recommendations

- Implement authentication (JWT/OAuth)
- Restrict access using authorization
- Limit response data
- Add rate limiting
- Validate user input

---

## 📂 Repository Structure
---

API-Security-Analysis/
│── Screenshots/
│── Report.pdf
│── Recommendations-and-Attack-Flow-Analysis.pdf
│── README.md

---

## 📸 Screenshots

Screenshots of API requests and responses are included in the **Screenshots** folder.

---

## 🎯 Conclusion

This project demonstrates how API security risks can be identified using simple testing methods.  
It highlights the importance of proper authentication, authorization, and data protection in modern applications.

---

## 👨‍💻 Prepared By
Vimal Raj R

