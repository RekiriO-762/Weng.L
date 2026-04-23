# Weng.I Website - Testing Log

**Date:** 23/04/26
**Tester:** Emlyn Ayi  
**Browser:** Chrome 

---

## Functional Tests

| # | Test Case | Expected Result | Actual Result | Pass/Fail | Notes |
|---|-----------|-----------------|---------------|-----------|-------|
| 1 | Page loads | Page opens without errors | | X Pass / O Fail | |
| 2 | Auto redirect | Automatically goes to page1_home.html | | X Pass / O Fail | |
| 3 | Redirect speed | Redirect happens within 0 seconds | | X Pass / O Fail | |
| 4 | Fallback link works | Click "Weng.I Home" link redirects manually | | X Pass / O Fail | |
| 5 | Fallback text displays | "Redirecting to Weng.I Home..." visible | | X Pass / O Fail | |
| 6 | Page title correct | Browser tab shows "Weng.I" | | X Pass / O Fail | |
| 7 | Back button works | Browser back button returns to index.html | | X Pass / O Fail | |

---

## Home Page (page1_home.html)

| # | Test | Expected | Result | Notes |
|---|------|----------|--------|-------|
| 1 | Logo displays | Logo visible, 64x64px | X Pass / O Fail | |
| 2 | Logo click → Home | Navigates to home page | x Pass / O Fail | |
| 3 | Search with text | Alert shows "Searching for..." | x Pass / O Fail | |
| 4 | Search empty | Alert shows error message | x Pass / O Fail | |
| 5 | Switch to French | All text in French | x Pass / O Fail | |
| 6 | Switch to Spanish | All text in Spanish | x Pass / O Fail | |
| 7 | Language persists | Same language on next page | x Pass / O Fail | |
| 8 | Language resets | Tab close → back to English | x Pass / O Fail | |
| 9 | Grey hover on nav | Background turns grey | x Pass / O Fail | |
| 10 | Top images load | 3 images visible | x Pass / O Fail | |
| 11 | Bottom images load | 2 images visible | x Pass / O Fail | |
| 12 | Animations work | Fade, pulse, zoom visible | x Pass / O Fail | |

---

## About Us Page (page2_about.html)

| # | Test | Expected | Result | Notes |
|---|------|----------|--------|-------|
| 1 | Headline displays | Text visible | X Pass / O Fail | |
| 2 | Paragraphs show | Two paragraphs with spacing | X Pass / O Fail | |
| 3 | Image loads | Robot hand image visible | X Pass / O Fail | |
| 4 | Language switch | French/Spanish works | X Pass / O Fail | |

---

## Products Page (page3_products.html)

| # | Test | Expected | Result | Notes |
|---|------|----------|--------|-------|
| 1 | 8 products display | 4-column grid visible | X Pass / O Fail | |
| 2 | Product images load | All 8 images visible | X Pass / O Fail | |
| 3 | Hover: levitate | Image lifts with shadow | X Pass / O Fail | |
| 4 | Hover: others darken | Non-hovered items fade | X Pass / O Fail | |
| 5 | Language switch | French/Spanish works | X Pass / O Fail | |

---

## Purpose Page (page4_purpose.html)

| # | Test | Expected | Result | Notes |
|---|------|----------|--------|-------|
| 1 | Text displays | Two paragraphs visible | X Pass / O Fail | |
| 2 | Three images load | All images visible | X Pass / O Fail | |
| 3 | Hover: labels appear | Text overlays show | X Pass / O Fail | |
| 4 | Language switch | French/Spanish works | X Pass / O Fail | |

---

## Newsroom Page (page5_newsroom.html)

| # | Test | Expected | Result | Notes |
|---|------|----------|--------|-------|
| 1 | Article displays | Title, image, 3 paragraphs | X Pass / O Fail | |
| 2 | Sidebar shows | 5 news items listed | X Pass / O Fail | |
| 3 | News items clickable | Alert shows on click | X Pass / O Fail | |
| 4 | Language switch | French/Spanish works | X Pass / O Fail | |

---

## Contact Us Page (page6_contact.html)

| # | Test | Expected | Result | Notes |
|---|------|----------|--------|-------|
| 1 | Form displays | All fields visible | X Pass / O Fail | |
| 2 | Empty submit | Error alert shows | X Pass / O Fail | |
| 3 | Invalid email | Error alert shows | X Pass / O Fail | |
| 4 | Valid submit | Thank you alert shows | X Pass / O Fail | |
| 5 | Contact info shows | Address, phone, email | X Pass /O Fail | |
| 6 | Language switch | French/Spanish works | X Pass / O Fail | |

---