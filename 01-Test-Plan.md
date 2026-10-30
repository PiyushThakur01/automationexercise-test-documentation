# Test Plan: Automation Exercise

| | |
|---|---|
| **Project** | Manual functional testing of Automation Exercise |
| **Application under test** | https://automationexercise.com (practice e-commerce website) |
| **Prepared by** | Piyush Singh |
| **Version / Date** | 1.0 / 29-10-2026 |

## 1. Objective
Verify that the main user flows of the Automation Exercise website (account creation, login, product search, cart, checkout, contact form and subscription) work as expected, and report any defects found with proper severity and priority.

## 2. Scope

**In scope**
- User signup, account creation and account deletion
- Login and logout
- Product listing, search, category and brand filters, product details
- Add to cart and cart management
- Checkout and payment flow (using dummy card data)
- Contact Us form
- Newsletter subscription

**Out of scope**
- Automation, performance, load and security penetration testing
- Mobile app and mobile browsers
- Third-party ads and social media links
- API testing (planned as a separate project)

## 3. Requirements to test

| Req ID | Requirement |
|---|---|
| REQ-01 | User registration and account management |
| REQ-02 | User login |
| REQ-03 | User logout |
| REQ-04 | Product listing, search, filter and details |
| REQ-05 | Add products to cart |
| REQ-06 | Cart management and calculations |
| REQ-07 | Checkout and payment |
| REQ-08 | Contact Us form |
| REQ-09 | Newsletter subscription |

## 4. Test approach
- **Type:** manual, black-box functional testing, plus basic UI checks
- **Design techniques:** equivalence partitioning, boundary value analysis, positive and negative testing, error guessing
- **Test case format:** ID, module, scenario, preconditions, steps, test data, expected result, actual result, status, priority, type, requirement ID (see `02-Test-Cases.xlsx`)
- **Defect handling:** every failed case is logged in the Bug Log with severity, priority, steps, expected and actual result, and a screenshot

## 5. Test environment

| Item | Detail |
|---|---|
| Browser | Google Chrome (latest; add exact version when executing) |
| Operating system | Windows 11 |
| Network | Standard broadband connection |
| Test data | Self-created test accounts and dummy payment details |

## 6. Entry and exit criteria

**Entry**
- Website is reachable and the home page loads
- Test cases are written and reviewed
- Test environment is ready

**Exit**
- All planned test cases have been executed
- All failed cases have a logged defect
- Test Summary Report is prepared

## 7. Defect severity and priority guide

| Severity | Meaning | Example |
|---|---|---|
| Critical | Core flow blocked, crash, data loss or security hole | Payment cannot be completed at all |
| Major | Important feature works wrongly, workaround exists | Cart total is calculated wrongly |
| Minor | Small functional or validation problem | Invalid mobile number accepted |
| Trivial | Cosmetic or text issue | Spelling or alignment problem |

Priority (High / Medium / Low) reflects how soon the defect should be fixed from a business point of view.

## 8. Risks and assumptions
- The site is a public practice website and can change or be unavailable without notice
- Some behaviors may be intentional for practice purposes; they are still reported with a note
- Third-party ads may interfere with page interactions
- Test accounts created during testing may be removed by the site owner

## 9. Deliverables
1. Test Plan (this document)
2. Test Cases with Traceability Matrix (`02-Test-Cases.xlsx`)
3. Bug Log (sheet in `02-Test-Cases.xlsx`)
4. Test Summary Report (`05-Test-Summary-Report.md`)
5. Screenshots of defects (`screenshots/`)

## 10. Schedule

| Day | Activity |
|---|---|
| 1 | Test plan and test case design |
| 2-4 | Test case review and refinement |
| 5-6 | Test execution and defect logging |
| 7 | Summary report and final review |
