# Test Cases

## Test Case Statuses
- Not Run
- Pass
- Fail
- Blocked
- Needs Investigation

---

# 1. Homepage (Начало)

### TC-001: Verify that the homepage loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open https://bielektra.com/.
  2. Wait for the page to finish loading.
- **Expected Result:** The homepage loads successfully without visible errors.
- **Actual Result:** The homepage loaded successfully.
- **Status:** Pass

### TC-002: Verify that homepage images load correctly
- **Preconditions:** Homepage is accessible.
- **Steps:**
  1. Open the homepage.
  2. Inspect the displayed images.
- **Expected Result:** All images load correctly and are displayed without broken-image indicators.
- **Actual Result:** Images were visible and loaded correctly during inspection.
- **Status:** Pass

### TC-003: Verify text animation during scrolling
- **Preconditions:** Homepage is accessible.
- **Steps:**
  1. Open the homepage.
  2. Locate animated text sections.
  3. Scroll through the sections.
  4. Observe the order and timing in which the text appears.
- **Expected Result:** Text animation displays in the intended sequence without unexpected timing or visual interruptions.
- **Actual Result:** In some text sections, the second part becomes visible before the first part has finished appearing.
- **Affected Pages:** Начало, За нас.
- **Status:** Fail
- **Related Bug:** BUG-002

### TC-004: Verify text formatting and underline positioning
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Locate text elements with underlining.
  3. Inspect the position of the underline relative to the letters.
  4. Repeat the check on the За нас and Проекти pages.
- **Expected Result:** Underlines appear beneath the text without overlapping the letters.
- **Actual Result:** The underline overlaps the text characters.
- **Affected Pages:** Начало, За нас, Проекти.
- **Status:** Fail
- **Related Bug:** BUG-001

---

# 2. About Us (За нас)

### TC-005: Verify that the About Us page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Click "За нас" in the navigation menu.
  3. Wait for the page to finish loading.
- **Expected Result:** The About Us page loads successfully without visible errors.
- **Actual Result:** The About Us page loaded successfully.
- **Status:** Pass

### TC-006: Verify About Us page text content and readability
- **Preconditions:** About Us page is accessible.
- **Steps:**
  1. Open the About Us page.
  2. Inspect the text content.
  3. Check whether the text is readable and properly displayed.
  4. Observe any text formatting or animation issues.
- **Expected Result:** Text is visible, readable, properly formatted, and not cut off.
- **Actual Result:** Text is readable. The underline positioning and text animation defects previously identified are also present on this page.
- **Status:** Pass
- **Related Bugs:** BUG-001, BUG-002

### TC-007: Verify that About Us page images load correctly
- **Preconditions:** About Us page is accessible.
- **Steps:**
  1. Open the About Us page.
  2. Scroll through the entire page.
  3. Inspect all displayed images.
- **Expected Result:** All images load correctly and are displayed without broken-image indicators or unexpected visual distortion.
- **Actual Result:** All images loaded correctly during inspection.
- **Status:** Pass

---

# 3. Services (Услуги)

### TC-008: Verify that the Services page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Click "Услуги" in the navigation menu.
  3. Wait for the page to finish loading.
- **Expected Result:** The Services page loads successfully.
- **Actual Result:** The Services page loaded successfully.
- **Status:** Pass

### TC-009: Verify that all listed services are displayed correctly
- **Preconditions:** Services page is accessible.
- **Steps:**
  1. Open the Services page.
  2. Inspect all listed services.
  3. Check that the service sections and titles are visible.
- **Expected Result:** All listed services are displayed correctly.
- **Actual Result:** All listed services were displayed correctly during inspection.
- **Status:** Pass

### TC-010: Verify that service descriptions and images are displayed correctly
- **Preconditions:** Services page is accessible.
- **Steps:**
  1. Open the Services page.
  2. Inspect the descriptions and images associated with the services.
  3. Check that the content is visible and properly displayed.
- **Expected Result:** Service descriptions and images are displayed correctly.
- **Actual Result:** Service descriptions and images were displayed correctly during inspection.
- **Status:** Pass

### TC-011: Verify that links or buttons related to services work correctly, if available
- **Preconditions:** Services page is accessible.
- **Steps:**
  1. Open the Services page.
  2. Locate links or buttons related to the services, if available.
  3. Click each available link or button.
  4. Check whether it performs the expected action.
- **Expected Result:** Available service-related links or buttons work correctly and lead to the expected destination or action.
- **Actual Result:** Available service-related links or buttons worked correctly during inspection.
- **Status:** Pass

---

# 4. Projects (Проекти)

### TC-012: Verify that the Projects page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Click "Проекти" in the navigation menu.
  3. Wait for the page to finish loading.
- **Expected Result:** The Projects page loads successfully.
- **Actual Result:** The Projects page loaded successfully.
- **Status:** Pass

### TC-013: Verify that all projects are displayed correctly
- **Preconditions:** Projects page is accessible.
- **Steps:**
  1. Open the Projects page.
  2. Inspect all displayed projects.
  3. Check that the project sections and titles are visible.
- **Expected Result:** All projects are displayed correctly.
- **Actual Result:** All projects were displayed correctly during inspection.
- **Status:** Pass

### TC-014: Verify that project images and descriptions are displayed correctly
- **Preconditions:** Projects page is accessible.
- **Steps:**
  1. Open the Projects page.
  2. Inspect the images and descriptions associated with each project.
  3. Check that the content is visible and properly displayed.
- **Expected Result:** Project images and descriptions are displayed correctly.
- **Actual Result:** Project images and descriptions were displayed correctly during inspection.
- **Status:** Pass
- **Related Bug:** BUG-001

### TC-015: Verify that project links or interactive elements work correctly, if available
- **Preconditions:** Projects page is accessible.
- **Steps:**
  1. Open the Projects page.
  2. Locate project links or interactive elements, if available.
  3. Click each available link or interactive element.
  4. Check whether it performs the expected action.
- **Expected Result:** Available project links or interactive elements work correctly and lead to the expected destination or action.
- **Actual Result:** Available project links or interactive elements worked correctly during inspection.
- **Status:** Pass

---

# 5. Contacts (Контакти)

### TC-016: Verify that the Contacts page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Click "Контакти" in the navigation menu.
  3. Wait for the page to finish loading.
- **Expected Result:** The Contacts page loads successfully.
- **Actual Result:** The Contacts page loaded successfully.
- **Status:** Pass

### TC-017: Verify that contact information is displayed correctly
- **Preconditions:** Contacts page is accessible.
- **Steps:**
  1. Open the Contacts page.
  2. Inspect the displayed contact information.
  3. Check that the information is visible and properly formatted.
- **Expected Result:** Contact information is displayed correctly and is readable.
- **Actual Result:** Contact information was displayed correctly during inspection.
- **Status:** Pass

### TC-018: Verify that email links work correctly
- **Preconditions:** Contacts page is accessible.
- **Steps:**
  1. Open the Contacts page.
  2. Locate the email address or email link.
  3. Click the email link.
  4. Observe the browser response.
- **Expected Result:** The email link uses the correct email protocol and attempts to open the default email application.
- **Actual Result:** The browser recognised the mailto: protocol, but no email application opened on the desktop.
- **Status:** Pass

### TC-019: Verify that phone links work correctly
- **Preconditions:** Contacts page is accessible.
- **Steps:**
  1. Open the Contacts page.
  2. Locate the phone number or phone link.
  3. Click the phone link.
  4. Observe the browser response.
- **Expected Result:** The phone link uses the correct telephone protocol and attempts to open a compatible calling application.
- **Actual Result:** The browser recognised the tel: protocol, but no calling application opened on the desktop.
- **Status:** Pass

### TC-020: Verify that contact forms work correctly, if available
- **Preconditions:** Contacts page is accessible and a contact form is available.
- **Steps:**
  1. Open the Contacts page.
  2. Locate the contact form.
  3. Test the available form fields and interactions.
  4. Check the form's response.
- **Expected Result:** The contact form works correctly and responds as expected.
- **Actual Result:** The contact form worked correctly during inspection.
- **Status:** Pass

### TC-021: Verify that the location or map is displayed correctly, if available
- **Preconditions:** Contacts page is accessible and a location or map is available.
- **Steps:**
  1. Open the Contacts page.
  2. Locate the displayed location or map.
  3. Inspect whether it loads and is displayed correctly.
- **Expected Result:** The location or map is displayed correctly.
- **Actual Result:** The location or map was displayed correctly during inspection.
- **Status:** Pass

---

# 6. Navigation

### TC-022: Verify that all five navigation links open the correct pages
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Locate the main navigation menu.
  3. Click each navigation link: Начало, За нас, Услуги, Проекти, and Контакти.
  4. Verify that each link opens its corresponding page.
- **Expected Result:** All five navigation links are clickable and open the correct corresponding pages.
- **Actual Result:** All five navigation links worked correctly and opened their corresponding pages.
- **Status:** Pass

### TC-023: Verify logo navigation
- **Preconditions:** Website is open on a page other than the homepage.
- **Steps:**
  1. Open any page other than the homepage.
  2. Click the website logo.
  3. Observe the destination.
- **Expected Result:** The user is redirected to the homepage.
- **Actual Result:** Clicking the website logo redirected to the homepage successfully.
- **Status:** Pass

### TC-028: Verify navigation consistency across all five pages
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open each of the five website pages.
  2. Inspect the navigation menu on each page.
  3. Click the available navigation links from each page.
  4. Verify that the links respond correctly and open the corresponding pages.
- **Expected Result:** Navigation works consistently across all five pages without broken links or navigation errors.
- **Actual Result:** Navigation worked consistently across all five pages during inspection.
- **Status:** Pass
---

# 7. Responsive Design

### TC-024: Verify homepage layout on desktop
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open https://bielektra.com/ in Google Chrome.
  2. Disable device emulation and use a desktop viewport.
  3. Inspect the homepage layout, navigation, text, and images.
- **Expected Result:** The homepage layout is displayed correctly on desktop without unintended overlapping, clipping, or alignment issues.
- **Actual Result:** The homepage layout works on desktop. Previously identified defects BUG-001 and BUG-002 remain present.
- **Status:** Pass
- **Related Bugs:** BUG-001, BUG-002

### TC-025: Verify all five pages on tablet
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open Chrome DevTools and enable Device Toolbar.
  2. Set the viewport to tablet size (768 × 1024).
  3. Open each page: Начало, За нас, Услуги, Проекти, and Контакти.
  4. Inspect the layout, text, images, navigation, and interactive elements on each page.
- **Expected Result:** All five pages should display correctly on tablet, with readable text, properly aligned content, and functional interactive elements.
- **Actual Result:** All five pages load and are accessible. The bottom text touches the page edges on Начало, За нас, Услуги, and Проекти. The dropdown options on Контакти do not fit properly. Previously identified defects BUG-001 and BUG-002 are also present on their affected pages. The homepage image appears with lower opacity on tablet.
- **Status:** Fail
- **Related Bugs:** BUG-001, BUG-002, RESP-001, RESP-002, RESP-003

### TC-026: Verify all five pages on mobile
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open Chrome DevTools and enable Device Toolbar.
  2. Set the viewport to mobile size (390 × 844).
  3. Open each page: Начало, За нас, Услуги, Проекти, and Контакти.
  4. Inspect the layout, text, images, navigation, and interactive elements on each page.
- **Expected Result:** All five pages should display correctly on mobile, with readable text, properly aligned content, and functional interactive elements.
- **Actual Result:** Услуги displays correctly. The existing underline defect BUG-001 is present on Начало, За нас, and Проекти. The existing text animation defect BUG-002 is present on Начало and За нас. The dropdown options on Контакти do not fit properly. The homepage image is intentionally not displayed on mobile.
- **Status:** Fail
- **Related Bugs:** BUG-001, BUG-002, RESP-002

### TC-027: Verify that no unintended horizontal scrolling occurs
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open Chrome DevTools and enable Device Toolbar.
  2. Set the viewport to tablet size (768 × 1024).
  3. Open each of the five pages and check for unintended horizontal scrolling.
  4. Repeat the check using mobile size (390 × 844).
  5. Distinguish unintended page-level horizontal scrolling from intentional horizontal scrolling within interactive elements, if available.
- **Expected Result:** No unintended horizontal scrolling should occur on any page at tablet or mobile viewport sizes.
- **Actual Result:** No unintended horizontal scrolling was observed during inspection.
- **Status:** Pass

---

## Notes
- Test cases will be expanded as the website's features are explored.
- Actual results and evidence will be documented during execution.
- Only confirmed defects will be added to the bug reports.
- Known defects are tracked separately in GitHub Issues.
- Email and phone link behaviour may depend on compatible applications being configured on the user's device.
- Responsive testing was performed using Chrome DevTools Device Toolbar.
- The homepage image opacity on tablet and its intentional absence on mobile are expected design behaviours, not defects.
- Responsive defects are tracked separately under RESP-001 and RESP-002.
