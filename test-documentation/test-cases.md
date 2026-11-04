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
- **Status:** Pass (with known defects)
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
  1. Click "Проекти" in the navigation menu.
- **Expected Result:** The Projects page loads successfully.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

---

# 5. Contacts (Контакти)

### TC-013: Verify that the Contacts page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Click "Контакти" in the navigation menu.
- **Expected Result:** The Contacts page loads successfully.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

---

# 6. Navigation

### TC-014: Verify navigation links
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Click each navigation link.
  3. Observe the destination.
- **Expected Result:** Each navigation link opens the correct page.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

### TC-015: Verify logo navigation
- **Preconditions:** Website is open on a page other than the homepage.
- **Steps:**
  1. Click the website logo.
- **Expected Result:** The user is redirected to the homepage.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

---

## Notes
- Test cases will be expanded as the website's features are explored.
- Actual results and evidence will be documented during execution.
- Only confirmed defects will be added to the bug reports.
- Known defects are tracked separately in GitHub Issues.
