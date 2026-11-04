# Test Execution Report

## 1. Project Information

- **Project:** Bielektra Website QA Testing
- **Website:** https://bielektra.com/
- **Testing Type:** Manual Testing
- **Tester:** Yoana Tsvetanova
- **Testing Period:** 04 November 2026 – Ongoing
- **Test Environment:** Google Chrome, Desktop, Operating System and screen resolution to be documented.

## 2. Testing Summary

Manual testing of the Homepage, About Us, and Services pages has been performed.

| Metric | Count |
|---|---:|
| Total Test Cases | 15 |
| Passed | 9 |
| Failed | 2 |
| Blocked | 0 |
| Needs Investigation | 0 |
| Not Run | 4 |

## 3. Test Execution Results

### Homepage – Начало

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-001 | Homepage loads successfully | Pass | N/A |
| TC-002 | Homepage images load correctly | Pass | N/A |
| TC-003 | Text animation during scrolling | Fail | BUG-002 |
| TC-004 | Text formatting and underline positioning | Fail | BUG-001 |

### About Us – За нас

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-005 | About Us page loads successfully | Pass | N/A |
| TC-006 | About Us text content and readability | Pass | BUG-001, BUG-002 |
| TC-007 | About Us images load correctly | Pass | N/A |

### Services – Услуги

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-008 | Services page loads successfully | Pass | N/A |
| TC-009 | All listed services are displayed correctly | Pass | N/A |
| TC-010 | Service descriptions and images are displayed correctly | Pass | N/A |
| TC-011 | Service-related links or buttons work correctly, if available | Pass | N/A |

### Projects – Проекти

Not Run

### Contacts – Контакти

Not Run

### Navigation

Not Run

### Responsive Design and Browser Compatibility

Not Run

## 4. Initial Observations

### OBS-001: Inconsistent text animation during scrolling
- **Description:** In some text sections, the second part of the text becomes visible before the first part has finished appearing. Other text sections appear to animate correctly.
- **Affected Pages:** Начало, За нас.
- **Status:** Reported as Defect
- **Related Bug:** BUG-002
- **Evidence:** Screen recording attached to GitHub Issue.

### OBS-002: Underline overlapping text
- **Description:** Underlined text appears to have the underline overlapping the letters instead of being positioned beneath them.
- **Affected Pages:** Начало, За нас, Проекти.
- **Status:** Reported as Defect
- **Related Bug:** BUG-001
- **Evidence:** Screenshot attached to GitHub Issue.

## 5. Defects Summary

Two defects have been identified, reproduced, and documented during manual testing.

| Bug ID | Description | Affected Pages | Severity | Status |
|---|---|---|---|---|
| BUG-001 | Underline overlaps text characters | Начало, За нас, Проекти | Low | Open |
| BUG-002 | Inconsistent text animation | Начало, За нас | Low | Open |

Both defects have been reported through GitHub Issues and linked to their corresponding test cases.

## 6. Conclusion

Manual testing of the Homepage, About Us, and Services pages has been completed.

A total of 11 test cases have been executed:
- 9 Passed
- 2 Failed

Two visual defects were identified, reproduced, and documented:
- BUG-001: Underline overlaps text characters.
- BUG-002: Inconsistent text animation.

All four Services test cases passed. Testing of the Projects and Contacts pages, navigation functionality, and responsive design and browser compatibility is pending.

## 7. Notes

- Test results will be updated as testing progresses.
- Confirmed defects are documented separately in GitHub Issues.
- Screenshots and screen recordings are attached as supporting evidence.
- Test cases are updated based on actual execution results.
- Known defects are tracked separately and do not automatically cause unrelated test cases to fail.
