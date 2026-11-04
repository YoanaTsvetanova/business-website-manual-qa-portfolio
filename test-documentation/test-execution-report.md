# Test Execution Report

## 1. Project Information

- **Project:** Bielektra Website QA Testing
- **Website:** https://bielektra.com/
- **Testing Type:** Manual Testing
- **Tester:** Yoana Tsvetanova
- **Testing Period:** 04 November 2026 – Ongoing
- **Test Environment:** Google Chrome, Windows (exact OS version and desktop resolution to be documented).
- **Responsive Testing:** Chrome DevTools Device Toolbar, tablet (768 × 1024) and mobile (390 × 844) viewports.

## 2. Testing Summary

Manual testing has been performed on the Homepage, About Us, Services, Projects, and Contacts pages, including desktop and responsive layout checks.

| Metric | Count |
|---|---:|
| Total Test Cases | 27 |
| Passed | 21 |
| Failed | 4 |
| Blocked | 0 |
| Needs Investigation | 0 |
| Not Run | 2 |

## 3. Test Execution Results

### Homepage – Начало

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-001 | Homepage loads successfully | Pass | N/A |
| TC-002 | Homepage images load correctly | Pass | N/A |
| TC-003 | Text animation during scrolling | Fail | BUG-002 |
| TC-004 | Text formatting and underline positioning | Fail | BUG-001 |
| TC-024 | Homepage desktop layout | Pass | BUG-001, BUG-002 |

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

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-012 | Projects page loads successfully | Pass | N/A |
| TC-013 | All projects are displayed correctly | Pass | N/A |
| TC-014 | Project images and descriptions are displayed correctly | Pass | BUG-001 |
| TC-015 | Project links or interactive elements work correctly, if available | Pass | N/A |

### Contacts – Контакти

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-016 | Contacts page loads successfully | Pass | N/A |
| TC-017 | Contact information is displayed correctly | Pass | N/A |
| TC-018 | Email links work correctly | Pass | N/A |
| TC-019 | Phone links work correctly | Pass | N/A |
| TC-020 | Contact forms work correctly, if available | Pass | N/A |
| TC-021 | Location or map is displayed correctly, if available | Pass | N/A |

### Navigation

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-022 | Navigation links work correctly | Not Run | N/A |
| TC-023 | Logo redirects to the Homepage | Not Run | N/A |

### Responsive Design

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-025 | All five pages – tablet layout (768 × 1024) | Fail | BUG-001, BUG-002, RESP-001, RESP-002, RESP-003 |
| TC-026 | All five pages – mobile layout (390 × 844) | Fail | BUG-001, BUG-002, RESP-002 |
| TC-027 | No unintended horizontal scrolling | Pass | N/A |

**Tablet testing results:**
- All five pages loaded and were accessible.
- Bottom text touched the page edges on Начало, За нас, Услуги, and Проекти.
- Dropdown options on Контакти did not fit properly.
- The Homepage image appeared with reduced opacity.
- Existing defects BUG-001 and BUG-002 were also present on their affected pages.

**Mobile testing results:**
- All five pages loaded and were accessible.
- Dropdown options on Контакти did not fit properly.
- Existing defects BUG-001 and BUG-002 were present on their affected pages.
- The Homepage image was not displayed on mobile. This is expected behaviour and was not reported as a defect.
- Услуги displayed correctly.

**Horizontal scrolling:** No unintended horizontal scrolling was observed during inspection of the tablet and mobile layouts.

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

Five defects have been identified during manual testing. Two are original visual defects and three are responsive design defects.

| Bug ID | Description | Affected Pages | Severity | Status |
|---|---|---|---|---|
| BUG-001 | Underline overlaps text characters | Начало, За нас, Проекти | Low | Open |
| BUG-002 | Inconsistent text animation | Начало, За нас | Low | Open |
| RESP-001 | Bottom text touches page edges on tablet | Начало, За нас, Услуги, Проекти | Low | Open |
| RESP-002 | Contact dropdown options do not fit properly | Контакти | Low | Open |
| RESP-003 | Homepage image appears with reduced opacity on tablet | Начало | Low | Pending confirmation |

Severity and priority classifications for the responsive defects are preliminary and may be revised.

BUG-001 and BUG-002, along with RESP-001 and RESP-002, have been documented through GitHub Issues. RESP-003 should also be documented in a GitHub Issue if it has not yet been created.

## 6. Conclusion

Manual testing has covered the Homepage, About Us, Services, Projects, and Contacts pages.

A total of 27 test cases have been documented:
- **21 Passed**
- **4 Failed**
- **2 Not Run**

Four test cases failed due to identified visual and responsive defects:
- TC-003: Inconsistent text animation.
- TC-004: Underline overlaps text characters.
- TC-025: Tablet responsive layout issues.
- TC-026: Mobile responsive layout issues.

Five defects have been identified:
- BUG-001: Underline overlaps text characters.
- BUG-002: Inconsistent text animation.
- RESP-001: Bottom text touches page edges on tablet.
- RESP-002: Contact dropdown options do not fit properly.
- RESP-003: Homepage image appears with reduced opacity on tablet.

The horizontal scrolling check passed. The Homepage image being absent on mobile was confirmed as expected behaviour and was not reported as a defect.

Navigation testing remains pending. Further testing and documentation will continue as the project progresses.

## 7. Notes

- Test results will be updated as testing progresses.
- Confirmed defects are documented separately in GitHub Issues.
- Screenshots and screen recordings are maintained as supporting test evidence.
- Test cases are updated based on actual execution results.
- Known defects are tracked separately and do not automatically cause unrelated test cases to fail.
- Email and phone link behaviour may depend on compatible applications being configured on the user's device.
- Responsive testing was performed using Chrome DevTools Device Toolbar.
- The Homepage image is intentionally hidden on mobile; its reduced opacity on tablet is considered a separate issue.
- Severity and priority ratings are preliminary and may change after further investigation.
