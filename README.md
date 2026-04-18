# 🤖 AICADO — Manual Test Report

This repository contains the complete manual testing documentation for the **AICADO** platform — an AI Agent creation and management system. All test cases, bug reports, and findings from the test cycle are organized here for transparency and traceability.

---

## 📁 Repository Structure

```
├── README.md                  # You are here
├── AICADO_Bug_Report.md       # High-level bug report summary
└── Aicado_task_main.md        # Full test cases + detailed bug report
```

---

## 🧪 Project Overview

| Field | Details |
|-------|---------|
| **Project** | AICADO |
| **Test Type** | Manual Testing |
| **Tester** | Kenan Sirinli |
| **Test Period** | March 15, 2026 – March 18, 2026 |
| **Platform** | Web |
| **Browser** | Chrome |
| **OS** | Windows / Android |
| **Base URL** | https://run.aicado.ai/dashboard |

---

## 📊 Test Results Summary

| Metric | Count |
|--------|-------|
| ✅ Total Test Cases | 48 |
| ✅ Passed | 43 |
| ❌ Failed | 5 |
| ⏸️ Blocked | 0 |

---

## 🐛 Bugs Found (5 Open)

| Bug ID | Title | Severity | Status |
|--------|-------|----------|--------|
| BUG-01 | AI agent name cannot be changed across all sections | Medium | 🔴 Open |
| BUG-02 | Unable to type in the input field | **Critical** | 🔴 Open |
| BUG-03 | File upload is not working | High | 🔴 Open |
| BUG-04 | Voice recording feature is not active | High | 🔴 Open |
| BUG-05 | Dropdown does not open when clicking "Choose an option" | High | 🔴 Open |

> ⚠️ **BUG-02 is critical** — it blocks the core functionality of the platform and must be fixed before release.

---

## 🔍 Scope of Testing

The following features were covered during this test cycle:

- **Authentication** — Login with valid/invalid credentials, empty fields, logout
- **Dashboard** — Widget loading, menu navigation, pagination
- **AI Agent Management** — Create, name, search, delete agents
- **Styling** — Background color, title color, text color, font size, font family, input field styling, avatar image upload, shadow effects
- **Features** — File upload, voice agent activation, preset messages
- **Tools** — Knowledge Base, Analytics
- **Team Management** — Create and delete teams
- **Plan & Billing** — Credits display, add credits, auto top-up, Stripe card integration, quota reminder
- **Publishing** — Publish agent, display options, connect domain, template selection

---

## 📄 File Descriptions

### `AICADO_Bug_Report.md`
A concise summary document covering:
- Test scope and environment
- Overall pass/fail metrics
- Short defect summary table
- Key issues and release recommendation

### `Aicado_task_main.md`
The full detailed test documentation with two sections:

**Sheet 1 — Test Cases**
Each of the 48 test cases includes:
- TC ID
- Title
- Precondition (URL)
- Step-by-step reproduction steps
- Expected result
- Pass/Fail status
- Priority (High / Medium / Low)

**Sheet 2 — Bug Report**
Each of the 5 bugs includes:
- Bug ID and title
- Description of the issue
- Step-by-step reproduction steps
- Actual vs. Expected result
- Priority level
- Link to screen recording / attachment

---

## ✅ Conclusion

The AICADO system is **partially functional**. 43 out of 48 test cases passed successfully. However, 5 significant bugs remain open — including one **critical** issue (input field not accepting text) that directly blocks core usage.

**Release is not recommended** until the critical and high-severity bugs are resolved.

---

## 📬 Contact

**Tester:** Kenan Sirinli  
**Test Period:** March 15–18, 2026
