# CleanCity: Waste Pickup Scheduler - Test Report
![Alt text](cleancity.png)

**Course:** Software Testing & Quality Assurance  
**Project Type:** Group Assessment
**Team Name:** KNS  
**Submission Date:** 2025-11-18

## Executive Summary
## Test Strategy and Approach
Manual and automated test cases were executed

## Manual Test Cases Summary

| Category | Range of Test Case IDs | Count |
|-----------|------------------------|--------|
| Functional | TC001 – TC010 | 10 |
| Non-Functional | TC011 – TC016 | 6 |
| UI (Accessibility + Cross-Browser) | TC017 – TC024 | 8 |
| Boundary & Edge Cases | TC025 – TC034 | 10 |
| **Total** |  | **34** |

---
Executive Summary

## Test Strategy and Approach
The testing strategy for this project combines static analysis and dynamic analysis (functional testing and non-functional testing) to ensure comprehensive quality coverage.

### 1. Static Analysis
We used SonarQube to analyze HTML, CSS, and JavaScript code in order to identify quality issues, vulnerabilities, and duplications. SonarQube generated a report with 124 issues, including 1 Critical, 87 High, and 36 Minor severity issues. These findings helped prioritize code improvements before dynamic testing.

### 2. Dynamic Analysis
Dynamic testing was performed to validate that the system behaves correctly under different scenarios and meets both functional and non-functional requirements. It included the following:

#### 2.1 Functional Testing
Manual Testing was done to verify all functional requirements  and Automated Testing using Selenium were done to ensure consistent functionality.

#### 2.2 Non-Functional Testing
Manual Testing: Usability, accessibility, and cross-browser compatibility checks were conducted using test scenarios and checklists.
Automated Testing: Performance, load, and response time tests were executed to ensure the system meets expected quality attributes.

---

Test Environment Details
Test Execution Summary
---
## Defect Analysis and Categorization
During the test execution phase (Phase 3) of the CleanCity project, defects were systematically identified, recorded and analysed to ensure the software met its functional and non-functional requirements. The testing team executed manual and automated test cases of the following fueatures of the application; authentication, dashboard functionality, waste pickup scheduling and accessibility.

Defects were categorized based on:
| **Severity** | **Description**                                                                                           |
| ------------ | ----------------------------------------------------------------------------------------------------------------------- |
| Critical     | Defects that impacts core functionality; must be fixed immediately.  |
| Major        | Defects that affect important features or workflows, but the system is still usable; should be addressed soon.          |
| Minor        | A medium defect appears when the system doesn’t meet certain criteria or exhibits some strange behaviours; functionality is not impacted |
| Cosmetic     | Visual or UI issues; do not affect system operation. |


---

Risk Assessment
Recommendations and Improvements
Test Metrics and KPIs
Jira/Github Kanban Reports: Include screenshots of Jira dashboards and reports






## Automated Test Cases Summary

| Category | Range of Test Case IDs | Count |
|-----------|------------------------|--------|
| Functional | TC035 – TC044 | 10 |
| Non-Functional | TC045 – TC050 | 6 |
| UI (Accessibility + Cross-Browser) | TC051 – TC058 | 8 |
| Boundary & Edge Cases | TC059 – TC067 | 9 |
| ** Total** |  | **33** |

---

## Overall Test Summary

| Category | Manual | Automated | Total |
|-----------|---------|------------|--------|
| Functional | 10 | 10 | **20** |
| Non-Functional | 6 | 6 | **12** |
| UI (Accessibility + Cross-Browser) | 8 | 8 | **16** |
| Boundary & Edge Cases | 10 | 9 | **19** |
| ** Grand Total** | **34** | **33** | **67** |
