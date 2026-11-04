# Test Plan

## 1. Project Overview

This project focuses on manual QA testing of a live business website to evaluate its functionality, usability, responsiveness, browser compatibility, and overall user experience.

The website contains five main pages: Homepage, About Us, Services, Projects, and Contacts.

## 2. Testing Objectives

- Identify functional and visual defects.
- Verify that website features work as expected.
- Evaluate website responsiveness across different screen sizes.
- Check form validation and user interactions.
- Verify navigation consistency across all website pages.
- Evaluate compatibility across different web browsers.
- Document test results and report identified defects.

## 3. Scope of Testing

Testing covers:

- Website navigation and links.
- Buttons and interactive elements.
- Forms and input validation.
- UI and usability.
- Responsive design (desktop, tablet, and mobile).
- Browser compatibility (Google Chrome, Mozilla Firefox, and Microsoft Edge).
- Images, text, and visual elements.
- Horizontal scrolling and layout behaviour.

## 4. Testing Types

- Functional Testing
- UI Testing
- Usability Testing
- Responsive Testing
- Exploratory Testing
- Cross-Browser Compatibility Testing

## 5. Tools

- Google Chrome
- Mozilla Firefox
- Microsoft Edge
- Chrome DevTools
- GitHub (test documentation and bug tracking)
- Google Sheets / Excel

## 6. Test Environment

- **Operating System:** Windows (exact version to be documented).
- **Browsers:** Google Chrome, Mozilla Firefox, Microsoft Edge.
- **Desktop Testing:** Desktop browser viewport.
- **Tablet Testing:** Chrome DevTools Device Toolbar, 768 × 1024.
- **Mobile Testing:** Chrome DevTools Device Toolbar, 390 × 844.
- **Website:** https://bielektra.com/

## 7. Test Execution

Manual test execution is performed using documented test scenarios and test cases.

Actual results are compared against expected results, and each test case is assigned an appropriate status:

- Pass
- Fail
- Blocked
- Not Run

Identified defects are documented in GitHub Issues with descriptions, reproduction steps, severity, priority, and supporting evidence where available.

Test execution results are maintained in the Test Execution Report.

## 8. Risks and Limitations

- Testing is performed on a live website.
- Destructive actions and operations involving real user data are avoided unless explicitly authorised.
- Responsive testing uses browser developer tools and emulated device viewports rather than physical devices.
- Browser compatibility testing is limited to the tested versions of Google Chrome, Mozilla Firefox, and Microsoft Edge.
- Email and phone link behaviour may depend on compatible applications being installed on the testing environment.
- Testing results represent the website's behaviour during the documented testing period.

