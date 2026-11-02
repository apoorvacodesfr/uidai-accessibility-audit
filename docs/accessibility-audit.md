# UIDAI Website – Accessibility Audit Report

## 1. Audit Overview

- **Website:** https://uidai.gov.in/
- **Testing tool:** Google Lighthouse
- **Manual testing:** Keyboard-only navigation and visual inspection
- **Audit type:** Accessibility baseline assessment

## 2. Lighthouse Results

- **Accessibility score:** 91/100
- **Automated findings:**
  - Buttons without accessible names.
  - Touch targets with insufficient size or spacing.
  - Heading elements not following sequential order.
  - Identical links with the same purpose.

Automated findings require manual verification before being classified as confirmed WCAG failures.

## 3. Identified Issues

### WEB-001: Buttons Without Accessible Names

- **Location:** Homepage – Updates section
- **WCAG:** 4.1.2 – Name, Role, Value
- **Evidence:** Lighthouse identified three buttons without accessible names.
- **Severity:** Medium (provisional)
- **User impact:** Screen reader users may not understand the purpose of these buttons.
- **Recommended fix:** Provide descriptive accessible names.
- **Status:** Open

### WEB-002: Small Carousel Touch Targets

- **Location:** Homepage – Banner carousel
- **WCAG:** 2.5.8 – Target Size (Minimum)
- **Evidence:** Lighthouse flagged carousel indicators. One inspected indicator measured approximately 8 × 8 CSS pixels.
- **Severity:** Medium (provisional)
- **User impact:** Users with motor difficulties may struggle to activate the indicators.
- **Recommended fix:** Increase the interactive target area or meet an applicable WCAG exception.
- **Status:** Needs verification

### WEB-003: Arrow Navigation Not Keyboard Accessible

- **Location:** Aadhaar Services page
- **WCAG:** 2.1.1 – Keyboard
- **Evidence:** An arrow navigation element worked with a mouse but was skipped during Tab navigation.
- **Severity:** Medium
- **User impact:** Keyboard-only users may be unable to access the linked destination.
- **Recommended fix:** Use a semantic link or make the interactive element keyboard-operable.
- **Status:** Open

### WEB-004: Tamil PDF Text Selection Problem

- **Location:** UIDAI – Downloadable Tamil PDF
- **WCAG:** To be determined
- **Evidence:** Text could not be selected normally during manual testing.
- **Severity:** Medium (provisional)
- **User impact:** Users may have difficulty copying or accessing document text through text-based tools.
- **Recommended fix:** Provide a properly structured PDF with an accessible Tamil text layer.
- **Status:** Needs verification

### WEB-005: Gallery Options Skipped During Keyboard Navigation

- **Location:** UIDAI – Media → Gallery
- **WCAG:** 2.1.1 – Keyboard
- **Evidence:** Tab navigation skipped the Images and Videos options. Mouse interaction was required to access Videos.
- **Severity:** Medium
- **User impact:** Keyboard-only users may be unable to access the gallery categories.
- **Recommended fix:** Make the gallery options keyboard-accessible.
- **Status:** Open

## 4. Conclusion

The audit identified potential accessibility barriers through automated and manual testing. Further technical verification is required for some findings. Addressing these issues can improve accessibility and usability for a wider range of users.
