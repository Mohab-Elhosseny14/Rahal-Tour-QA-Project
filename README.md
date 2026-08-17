# Rahal Tour - Manual QA Testing Project

Manual testing project for **Rahal Tour**, a travel booking mobile application.

I tested the main features of the application, created test cases, executed them using Jira with Zephyr, and reported the bugs I found.

## Project Summary

| Metric | Result |
|---|---:|
| Total Test Cases | 101 |
| Passed | 92 |
| Failed | 9 |
| Pass Rate | 91.1% |
| Bugs Found | 9 |
| Bugs Fixed & Closed | 9 |

## Areas Tested

- Registration
- Login & Authentication
- Home Screen
- Settings / Profile
- Logout
- Navigation

## Testing Types

- Functional Testing
- Negative Testing
- Boundary Value Analysis
- Equivalence Partitioning
- Basic Security Testing
- UI / Navigation Testing

For security testing, I manually tested simple XSS and SQL Injection payloads in the Email and Password fields.

## Test Cases

I created and executed **101 test cases**.

Detailed test cases are provided for a selected group of test cases, including the test cases related to the reported bugs. The remaining test cases are included with their execution status (Pass/Fail).

The detailed test cases include:

- Preconditions
- Steps
- Test Data
- Expected Result
- Actual Result
- Status

## Defects

I found **9 defects** during testing.

The defects were reported in Jira and include issues related to:

- Phone number validation
- Name field length validation
- Age validation
- Forgot Password
- Session persistence
- Password reset

All 9 reported defects were fixed by the Flutter developer and retested before being closed.

## Tools

- Jira
- Zephyr
- Microsoft Excel

## Project Files

- **[Rahal_Tour_QA_Testing.xlsx](Rahal_Tour_QA_Testing.xlsx)**  
  Contains the test cases, detailed test cases, test execution results, test summary, and bug reports.

- **Evidence/**  
  Contains screenshots related to the reported bugs.
