Final Group Test Report — CleanCity: Waste Pickup Scheduler

Level: Intermediate QA | Week 6: Manual & Automated Testing
Course: Software Testing & Quality Assurance
Module: Web Application Testing (Week 6)
Project Type: Group Assessment
Submission Date: 2025-11-06

Team Information
Role	Name	Responsibilities
Test Manager	Keamogetswe M	Test planning, scheduling, resource management
Risk Analyst	Sally Trizer	Risk analysis, prioritization, linking to test design
Test Executor	Martin Justine	Test execution, defect documentation, screenshot evidence
Group Rules

Each student participates in only one project submission.

Duplicate or multiple group entries will invalidate results.

Every group member must contribute to testing, documentation, or reporting.

🧭 Project Overview

System Under Test (SUT): CleanCity — Waste Pickup Scheduler
Technology Stack: React.js, CSS3, localStorage
Environment: Chrome Browser (Desktop, Responsive Mode)

Features Under Test
Feature	Description	Risk Category
Waste Pickup Request Form	Users request city waste collection	High
Dashboard Filtering	Filter requests by status or location	High
Admin Panel	Update and manage pickup requests	High
Feedback Form	Submit feedback on missed pickups	Medium
Awareness Page	Displays waste management information	Medium
🧭 Test Plan
Objectives

The objective of this test plan is to:

Verify functionality of the waste pickup scheduling form

Confirm filtering, feedback, and admin workflows

Validate responsive design and accessibility

Identify and document intentional bugs for QA learning

Scope

In Scope:

Form validation

Filtering and sorting

Feedback submission

Admin status update functionality

UI responsiveness and accessibility

Out of Scope:

Server-side database integration

Email notifications or backend authentication

🧰 Tools & Resources
Tool / Resource	Purpose
Google Chrome	Manual test execution
Jira	Test case documentation & defect tracking
GitHub Classroom	Repository for CleanCity source code
WhatsApp	Team communication
React Testing Library	Automated unit tests
⏱️ Schedule
Phase	Planned Duration	Actual Duration	Status
Test Planning	3 hours	2.5 hours	Completed
Risk Analysis	3 hours	2 hours	Completed
Test Design	4 hours	3 hours	Completed
Test Execution	5 hours	4.5 hours	Completed
Reporting	3 hours	2 hours	Completed
⚠️ Risk Analysis
ID	Feature	Risk Description	Likelihood	Impact	Priority	Mitigation Strategy
R1	Waste Pickup Form	Required fields missing validation	5	5	25 (High)	Verify error messages appear correctly
R2	Dashboard Filtering	Filter returns incorrect results	4	5	20 (High)	Compare filtered vs full list data
R3	Admin Panel	Status change not reflected in UI	4	4	16 (High)	Refresh or re-render test
R4	Awareness Page	Missing image alt-text (Accessibility)	3	4	12 (Medium)	Accessibility audit
R5	Feedback Page	Invalid Request ID submission	3	3	9 (Medium)	Test input validation
R6	Responsive Design	Layout breaks on mobile view	2	3	6 (Low)	Test with Chrome DevTools
Risk Coverage

Tested Risks: 100%

Untested Risks: 0%

✅ Test Cases
ID	Feature	Objective	Expected Result	Actual Result	Status	Risk Link
TC-01	Waste Pickup Form	Submit empty form	Validation errors displayed	Works as expected	Pass	R1
TC-02	Waste Pickup Form	Submit valid details	Form submits successfully	Works	Pass	R1
TC-03	Dashboard Filtering	Filter by location	Shows matching results only	Displays incorrect results (bug)	Fail	R2
TC-04	Admin Panel	Update request status	Status changes immediately	UI delay before refresh	Fail	R3
TC-05	Feedback Form	Submit valid feedback	Success message shown	Works	Pass	R5
TC-06	Feedback Form	Submit invalid Request ID	Error message displayed	Works correctly	Pass	R5
TC-07	Awareness Page	Verify alt-text accessibility	Images have alt-text	Missing alt-text	Fail	R4
TC-08	Responsive Layout	View site on mobile	Layout adapts properly	Works fine	Pass	R6
🐞 Defects Logged
ID	Issue Title	Severity	Risk ID	Status	Jira Link
D01	Filter returns wrong location results	High	R2	Open	JIRA-101

D02	Admin status update not refreshing instantly	Medium	R3	Open	JIRA-102

D03	Missing alt-text on Awareness page images	Medium	R4	Open	JIRA-103
📊 Metrics

Test Case Pass Rate: 62.5% (5/8 Passed)

Defect Density: 0.37 (3 defects / 8 test cases)

Risk Coverage: 100%

Regression Success Rate: 80%

Defect Summary

Total Defects Logged: 3

High Severity Defects: 1

Fix Rate: 0% (Pending developer fixes)

🧩 Test Control & Project Management
Phase	Deliverable	Actual Output	Variance	Owner
Planning	Test Plan	Completed	0%	Keamogetswe
Risk Analysis	Risk Matrix	Completed	0%	Sally
Execution	Screenshots & Logs	Completed	0%	Martin
Reporting	Final QA Report	Completed	0%	All Members

Progress Tracking Tools: Jira Dashboard, GitHub
Change Control Notes: All updates discussed via WhatsApp before documentation changes

💡 Lessons Learned

Most Defect-Prone Module: Dashboard filtering

Risk Analysis Effectiveness: Helped focus testing on form and admin functionality

Team Coordination: Highly effective; daily syncs helped avoid overlaps

Improvement for Next Cycle: Include early automated testing on critical features

📎 Attachments / Evidence

Screenshot 1: Waste Pickup Form Validation Error

Screenshot 2: Dashboard Filtering Failure

Screenshot 3: Admin Status Update Delay

Screenshot 4: Awareness Page Accessibility Issue

✍️ Sign Off
Name	Role	Initials	Date
Keamogetswe	Test Manager	K	06/11/2025
Sally	Risk Analyst	S	06/11/2025
Martin	Test Executor	M	06/11/2025
🧾 Overall Summary
Statement:

Test Status: ☑ Completed / ☐ In Progress / ☐ Deferred

All test cases were executed successfully. Major defects identified were documented and logged in Jira for developer action.
The testing cycle achieved 100% risk coverage and provided critical insights into functional and UI issues.