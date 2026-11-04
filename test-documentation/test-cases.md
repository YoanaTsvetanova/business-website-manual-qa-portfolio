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

### TC-003: Verify homepage content and visual elements during scrolling
- **Preconditions:** Homepage is accessible.
- **Steps:**
  1. Open the homepage.
  2. Locate the animated text section.
  3. Scroll down through the section.
  4. Observe the order and timing in which the text appears.
- **Expected Result:** Text appears in the intended order without unexpected delays or visual interruptions.
- **Actual Result:** The second part of the text becomes visible while the first part is still appearing.
- **Status:** Needs Investigation

### TC-004: Verify text formatting and underline positioning
- **Preconditions:** Homepage is accessible.
- **Steps:**
  1. Open the homepage.
  2. Locate text elements with underlining.
  3. Inspect the position of the underline relative to the letters.
- **Expected Result:** Underlines appear beneath the text without overlapping the letters.
- **Actual Result:** The underline appears to overlap the text.
- **Status:** Fail
-**Related Bug:** BUG-001
  
---

# 2. About Us (За нас)

### TC-005: Verify that the About Us page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Click "За нас" in the navigation menu.
- **Expected Result:** The About Us page loads successfully.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

---

# 3. Services (Услуги)

### TC-006: Verify that the Services page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Click "Услуги" in the navigation menu.
- **Expected Result:** The Services page loads successfully.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

---

# 4. Projects (Проекти)

### TC-007: Verify that the Projects page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Click "Проекти" in the navigation menu.
- **Expected Result:** The Projects page loads successfully.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

---

# 5. Contacts (Контакти)

### TC-008: Verify that the Contacts page loads successfully
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Click "Контакти" in the navigation menu.
- **Expected Result:** The Contacts page loads successfully.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

---

# 6. Navigation

### TC-009: Verify navigation links
- **Preconditions:** Website is accessible.
- **Steps:**
  1. Open the homepage.
  2. Click each navigation link.
  3. Observe the destination.
- **Expected Result:** Each navigation link opens the correct page.
- **Actual Result:** Not yet tested.
- **Status:** Not Run

### TC-010: Verify logo navigation
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
