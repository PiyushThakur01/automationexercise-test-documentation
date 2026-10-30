# Test Summary Report: Automation Exercise

| **Application** | https://automationexercise.com |
| **Tested by** | Piyush Singh |
| **Test period** | October 2026 to October 2026 |
| **Environment** | Google Chrome 156.0.8078.80, Windows 11 |

## 1. Overview
Manual functional testing was carried out on the main user flows of the website as described in `01-Test-Plan.md`.

## 2. Execution results

| Metric | Count |
| Total test cases | 59 |
| Passed | 53 |
| Failed | 06 |
| Blocked | 00 |
| Not executed | 00 |
| Pass rate | 89.8% |

## 3. Results by module

| Module | Total | Passed | Failed | Blocked |
|---|---|---|---|---|
| Signup | 11 | 11 - F | F | 0 |
| Login | 8 | 8 - F | F | 0 |
| Logout | 2 | 2 - F | F | 0 |
| Products | 9 | 9 - F | F | 0 |
| Cart | 10 | 10 - F | F | 0 |
| Checkout | 9 | 9 - F | F | 0 |
| Contact Us | 6 | 6 - F | F | 0 |
| Subscription | 4 | 4 - F | F | 0 |

## 4. Defects found

| Severity | Count |

| Critical | 0 |
| Major | 3 |
| Minor | 3 |
| Trivial | 0 |

**Key defects**
1. BUG-0__: Cart accepts a negative product quantity (missing validation), Major
2. BUG-0__: Card expiry date is not validated at checkout, Major
3. BUG-0__: (pick the next most important one from your Bug Log)

## 5. Observations
-  Validation was the main weakness: the defects found were mostly missing or incomplete input validation in the Cart and Checkout flows.
- No cases were blocked and no Critical defects were found.
- The 3 Minor defects are usability or message issues that do not stop the user from completing a task.

## 6. Conclusion and recommendations
[Short conclusion, e.g. whether the application is ready for release from a QA point of view and which defects should be fixed first.]
