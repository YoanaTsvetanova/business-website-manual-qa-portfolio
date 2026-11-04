# Test Execution Report

## 1. Project Information

- **Project:** Bielektra Website QA Testing
- **Website:** https://bielektra.com/
- **Testing Type:** Manual Testing
- **Tester:** Yoana Tsvetanova
- **Testing Period:** 04 November 2026 – Ongoing
- **Test Environment:** To be documented

## 2. Testing Summary

Initial manual testing of the homepage has been performed.

| Metric | Count |
|---|---:|
| Total Test Cases | 32 |
| Passed | 2 |
| Failed | 0 |
| Blocked | 0 |
| Needs Investigation | 2 |
| Not Run | 28 |

## 3. Test Execution Results

### Homepage – Начало

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-001 | Homepage loads successfully | Pass | N/A |
| TC-002 | Homepage images load correctly | Pass | N/A |
| TC-003 | Homepage content and visual elements display correctly | Fail | BUG-002 |
| TC-004 | Text formatting and presentation | Fail | BUG-001 |

### About Us – За нас

Not Run

### Services – Услуги

Not Run

### Projects – Проекти

Not Run

### Contacts – Контакти

Not Run

### Navigation, Responsive Design and Browser Compatibility

Not Run

## 4. Initial Observations

### OBS-001: Inconsistent text animation during scrolling
- **Description:** In some homepage text sections, the second part of the text becomes visible before the first part has finished appearing. Other text sections appear to animate correctly.
- **Status:** Reported as Defect
- **Related Bug:** BUG-002
- **Evidence:** Screen recording attached to GitHub Issue.

### OBS-002: Underline overlapping text
- **Description:** Underlined text appears to have the underline overlapping the letters instead of being positioned beneath them.
- **Status:** Reported as Defect
- **Related Bug:** BUG-001
- **Evidence:** Screenshot attached to GitHub Issue.

## 5. Defects Summary

Two defects have been identified, reproduced, and documented during homepage testing.

| Bug ID | Description | Severity | Status |
|---|---|---|---|
| BUG-001 | Underline overlaps text characters | Low | Open |
| BUG-002 | Inconsistent text animation across homepage sections | Low | Open |

Both defects have been reported through GitHub Issues and linked to their corresponding test cases.
## 6. Conclusion

Initial homepage testing has been completed for two test cases, both of which passed.

Two additional visual observations were identified and require further investigation.

Testing of the remaining website pages and functionality is pending.

## 7. Notes

- Test results will be updated as testing progresses.
- Confirmed defects will be documented separately.
- Screenshots and screen recordings will be attached as evidence.
- Test cases will be updated when actual results are available.
