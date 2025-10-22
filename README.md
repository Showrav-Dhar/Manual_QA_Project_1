# Manual_QA_Project_1 — Manual Testing Portfolio (SauceDemo)

This repository showcases an end‑to‑end **manual QA project** on the public demo site **SauceDemo (Swag Labs)**. It is designed to demonstrate my test planning, scenario design, traceability, execution discipline, and defect reporting skills.

> **What’s inside:** A complete, set of QA artifacts — **Test Plan**, **Test Scenarios**, **RTM**, **Detailed Test Cases**, **Test Execution Results**, and a **Bug Report** — all linked and consistent.

---

## 📌 Project Objectives

* Validate the core shopper journey: **login → browse/sort → cart → checkout**.
* Demonstrate **risk‑based** and **user‑journey‑focused** test strategy with forward/backward **traceability**.
* Test the behaviour of all kinds of user accounts - **standard_user**, **locked_out_user**, **problem_use**r, **performance_glitch_user**, **error_user**, **visual_user**
* Produce clean, auditable artifacts suitable for a QA portfolio and real‑world processes.

---

## 🔗 Repository Structure

* **[1_Test_Plan_Sauce_Demo.pdf](https://github.com/Showrav-Dhar/Manual_QA_Project_1/blob/main/1_Test_Plan_Sauce_Demo.pdf)** — overall scope, strategy, risks, environments, entry/exit criteria, and schedule.
* **[2_Test_Scenarios_Sauce_Demo.xlsx](https://github.com/Showrav-Dhar/Manual_QA_Project_1/blob/main/2_Test_Scenarios_Sauce_Demo.xlsx)** — prioritized, high‑level scenarios with requirement IDs.
* **[3_RTM_Sauce_Demo.xlsx](https://github.com/Showrav-Dhar/Manual_QA_Project_1/blob/main/3_RTM_Sauce_Demo.xlsx)** — Requirement ⇄ Scenario ⇄ (Test Case) mapping for full coverage.
* **[4_Test_Cases_Sauce_Demo.xlsx](https://github.com/Showrav-Dhar/Manual_QA_Project_1/blob/main/4_Test_Cases_Sauce_Demo.xlsx)** — step‑by‑step test cases (with data & expected results).
* **[5_Test_Execution_Result_Sauce_Demo.xlsx](https://github.com/Showrav-Dhar/Manual_QA_Project_1/blob/main/5_Test_Execution_Result_Sauce_Demo.xlsx)** — execution log (Smoke + Functional/Regression), results, evidence links.
* **[6_Bug_Report_Sauce_Demo.xlsx](https://github.com/Showrav-Dhar/Manual_QA_Project_1/blob/main/6_Bug_Report_Sauce_Demo.xlsx)** — concise defect log (summary, steps, expected vs actual, severity/priority, screenshot).

> File names are prefixed numerically to reflect the real workflow order from **plan → design → trace → execute → report**.

---

## 🧭 Scope (In/Out)

**In scope:**

* **Authentication:** positive login, negative (invalid/locked out), logout.
* **Catalog:** inventory loads, sort (A→Z, Z→A, price low→high, high→low), product details.
* **Cart:** add/remove items, badge count, state persistence.
* **Checkout:** data validation, overview accuracy, finish flow.
* **Basic UX:** labels, error clarity, menu/footer/social links (smoke level).

**Out of scope:** Full performance, security, and accessibility audits; mobile device matrix; back‑office/admin modules; real payment/email flows.

---

## 🧪 Test Strategy Highlights

* **Approach:** Risk‑based, user‑journey first; **shift‑left** clarity (scenarios before cases); evidence‑driven.
* **Levels:** Smoke → Functional; plus short **exploratory** passes.
* **Design techniques:** Equivalence classes, boundary values (checkout form), decision tables (auth), state transitions (cart add/remove).
* **Prioritization:** P0 (happy path blockers), P1 (core variants), P2 (peripheral/edges).
* **Traceability:** RTM links **Requirements → Scenarios → Test Cases → Results/Defects**.

---

## 🧩 How to Read the Artifacts

1. **Start with the Test Plan** to understand scope, risks, and environment.
2. **Open Test Scenarios** to see the high‑level journeys (TS‑IDs) tied to **REQ‑IDs**.
3. **Check the RTM** to confirm coverage from requirements down to execution.
4. **Review Test Cases** (TC‑IDs) for reproducible steps and expected results.
5. **Inspect Execution Results** to see pass/fail, evidence links, and timing.
6. **Look at the Bug Report** to evaluate defect quality (clear titles, steps, expected vs actual, severity/priority, screenshots).

---

## 🐛 Defect Logging (examples)

Each bug entry includes: **Summary**, **Steps to Reproduce**, **Expected vs Actual**, **Severity (S1–S4)**, **Priority (P0–P2)**, and **Screenshot** link.

> See **6_Bug_Report_Sauce_Demo.xlsx** for full details and evidence.

---

## 🛠️ Tools & Environment

* **Authoring/Reporting:** Excel, PDF, screenshots.
* **Browsers:** Chrome (latest), Firefox (latest) on desktop.
* **AUT:** SauceDemo (public demo). No real payments/email required.

---

## 🎯 Skills Demonstrated

* Test planning & risk management
* Scenario derivation & traceability (**RTM**)
* Detailed test case design (clear oracles, repeatability)
* Evidence‑based execution & concise status reporting
* Defect reporting with actionable steps and prioritization
  
---

## 📣 Why this project?

This repo mirrors a realistic QA workflow while keeping scope focused. It demonstrates how one would structure manual testing in a new team: start from a crisp **Test Plan**, drive **traceable** design, capture **evidence**, report **actionable defects**, and **communicate status** clearly.
