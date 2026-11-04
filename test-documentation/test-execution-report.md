# Test Execution Report

## 1. Project Information

- **Project:** Bielektra Website QA Testing
- **Website:** https://bielektra.com/
- **Testing Type:** Manual Testing
- **Tester:** Yoana Tsvetanova
- **Testing Period:** 04 November 2026 – Ongoing
- **Test Environment:** Google Chrome, Mozilla Firefox, Microsoft Edge, Windows (exact OS version and desktop resolution to be documented).
- **Responsive Testing:** Chrome DevTools Device Toolbar, tablet (768 × 1024) and mobile (390 × 844) viewports.

## 2. Testing Summary

Manual testing has been performed on the Homepage, About Us, Services, Projects, and Contacts pages, including desktop, responsive layout, navigation, and browser compatibility checks.

| Metric | Count |
|---|---:|
| Total Test Cases | 31 |
| Passed | 27 |
| Failed | 4 |
| Blocked | 0 |
| Needs Investigation | 0 |
| Not Run | 0 |

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

**Environment note:** The browser recognised the email and phone link protocols (`mailto:` and `tel:`). No compatible desktop applications opened. This was treated as an environment limitation rather than a confirmed website defect.

### Navigation

| Test Case ID | Test Scenario | Status | Related Bug ID |
|---|---|---|---|
| TC-022 | All five navigation links open the correct pages | Pass | N/A |
| TC-023 | Website logo redirects to the Homepage | Pass | N/A |
| TC-028 | Navigation works consistently across all five pages | Pass | N/A |

**Navigation testing results:**
- All five navigation links were clickable and responded correctly.
- Each navigation link opened its corresponding page.
- Clicking the website logo redirected to the Homepage.
- Navigation worked consistently across all five pages.

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

### Browser Compatibility

| Test Case ID | Test Scenario | Browser | Status | Related Bug ID |
|---|---|---|---|---|
| TC-029 | Verify website compatibility | Google Chrome | Pass | BUG-001, BUG-002, RESP-001, RESP-002, RESP-003 |
| TC-030 | Verify website compatibility | Mozilla Firefox | Pass | BUG-001, BUG-002, RESP-001, RESP-002, RESP-003 |
| TC-031 | Verify website compatibility | Microsoft Edge | Pass | BUG-001, BUG-002, RESP-001, RESP-002, RESP-003 |

**Browser compatibility testing results:**
- The website was tested in Google Chrome, Mozilla Firefox, and Microsoft Edge.
- All five pages were checked in each browser.
- Navigation, logo functionality, page layout, text, images, and interactive elements were inspected.
- The website displayed the same behaviour and known issues in all three browsers.
- No additional browser-specific issues were identified.

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
| RESP-003 | Homepage image appears with reduced opacity on tablet | Начало | Low | Open |

**Additional notes:**
- BUG-001 and BUG-002 were reproduced during responsive testing.
- RESP-001 and RESP-002 were observed during tablet testing; RESP-002 was also observed during mobile testing.
- RESP-003 concerns the reduced opacity of the Homepage image on tablet. The image being absent on mobile is expected behaviour and is not a defect.
- No additional browser-specific defects were identified during compatibility testing.

## 6. Conclusion

Manual testing covered all five website pages, including desktop layout, tablet and mobile responsiveness, navigation, and browser compatibility.

A total of 31 test cases were executed:
- 27 test cases passed.
- 4 test cases failed.
- No test cases remain unexecuted.

The website was tested in Google Chrome, Mozilla Firefox, and Microsoft Edge. The same behaviour and known defects were observed across all three browsers, with no additional browser-specific issues identified.

Five defects were identified and documented: BUG-001, BUG-002, RESP-001, RESP-002, and RESP-003. All are currently marked as Open.

The main areas requiring improvement are text formatting, text animation, and responsive layout on tablet and mobile devices.

Further testing should be performed after the reported defects have been fixed to verify the corrections and ensure that no regressions have been introduced.
