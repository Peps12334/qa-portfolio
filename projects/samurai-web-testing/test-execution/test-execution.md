# Test Execution

## 1. Document Information

| Field               | Value                 |
| ------------------- | --------------------- |
| Project             | Samurai Web Testing   |
| Application         | Samurai Food Delivery |
| Test Execution Type | Manual                |
| Tester              | Artem                 |
| Execution Status    | In Progress           |
| Start Date          | —                     |
| End Date            | —                     |

---

## 2. Test Execution Summary

| Metric           | Count |
| ---------------- | ----: |
| Total Test Cases |       |
| Passed           |       |
| Failed           |       |
| Blocked          |       |
| Not Run          |       |
| Pass Rate        |       |

> **Status definitions:**
>
> * **PASS** — actual behavior matches the expected result.
> * **FAIL** — actual behavior does not match the expected result.
> * **BLOCKED** — the test cannot be completed because of an external blocker.
> * **NOT RUN** — the test has not been executed yet.

---

## 3. Test Execution Results

### TC-001 — Homepage

| ID        | Test Case                                  | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ------------------------------------------ | -------- | ------ | ------------- | ------ | ----- |
| TC-001-01 | Homepage loads successfully                | High     | PASS   | All interface load success|        |       |
| TC-001-02 | Homepage navigation works correctly        | High     |        |               |        |       |
| TC-001-03 | Main page elements are displayed correctly | Medium   |        |               |        |       |
| TC-001-04 | Homepage works after page refresh          | Medium   |        |               |        |       |

---

### TC-002 — Navigation

| ID        | Test Case                                       | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ----------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-002-01 | Navigation menu opens correctly                 | High     |        |               |        |       |
| TC-002-02 | Navigation links lead to correct pages/sections | High     |        |               |        |       |
| TC-002-03 | Browser Back/Forward navigation works correctly | Medium   |        |               |        |       |

---

### TC-003 — Product Catalog

| ID        | Test Case                                        | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ------------------------------------------------ | -------- | ------ | ------------- | ------ | ----- |
| TC-003-01 | Product catalog opens successfully               | High     |        |               |        |       |
| TC-003-02 | Product categories are displayed correctly       | High     |        |               |        |       |
| TC-003-03 | Product images are displayed correctly           | Medium   |        |               |        |       |
| TC-003-04 | Product names and prices are displayed correctly | High     |        |               |        |       |
| TC-003-05 | Product cards can be opened                      | High     |        |               |        |       |

---

### TC-004 — Product Details

| ID        | Test Case                                         | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ------------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-004-01 | Product details page opens correctly              | High     |        |               |        |       |
| TC-004-02 | Product information is displayed correctly        | High     |        |               |        |       |
| TC-004-03 | Product price is displayed correctly              | High     |        |               |        |       |
| TC-004-04 | Product can be added to cart from product details | Critical |        |               |        |       |

---

### TC-005 — Search

| ID        | Test Case                                      | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ---------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-005-01 | Search field is available                      | Medium   |        |               |        |       |
| TC-005-02 | Search returns relevant products               | High     |        |               |        |       |
| TC-005-03 | Search handles non-existing products correctly | Medium   |        |               |        |       |
| TC-005-04 | Search handles empty input correctly           | Medium   |        |               |        |       |

---

### TC-006 — Shopping Cart

| ID        | Test Case                               | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | --------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-006-01 | Product can be added to cart            | Critical |        |               |        |       |
| TC-006-02 | Added product appears in cart           | Critical |        |               |        |       |
| TC-006-03 | Product information in cart is correct  | High     |        |               |        |       |
| TC-006-04 | Product can be removed from cart        | High     |        |               |        |       |
| TC-006-05 | Cart remains correct after page refresh | Medium   |        |               |        |       |

---

### TC-007 — Product Quantity Management

| ID        | Test Case                                | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ---------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-007-01 | Product quantity can be increased        | High     |        |               |        |       |
| TC-007-02 | Product quantity can be decreased        | High     |        |               |        |       |
| TC-007-03 | Minimum quantity is handled correctly    | Medium   |        |               |        |       |
| TC-007-04 | Cart total updates after quantity change | Critical |        |               |        |       |

---

### TC-008 — Pricing and Discounts

| ID        | Test Case                                   | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-008-01 | Product price matches the displayed price   | High     |        |               |        |       |
| TC-008-02 | Discounted price is displayed correctly     | High     |        |               |        |       |
| TC-008-03 | Cart total is calculated correctly          | Critical |        |               |        |       |
| TC-008-04 | Discount is correctly reflected in the cart | High     |        |               |        |       |

---

### TC-009 — Delivery and Pickup

| ID        | Test Case                                             | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ----------------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-009-01 | Delivery option can be selected                       | High     |        |               |        |       |
| TC-009-02 | Pickup option can be selected                         | High     |        |               |        |       |
| TC-009-03 | Switching between delivery and pickup works correctly | High     |        |               |        |       |
| TC-009-04 | Delivery-related information is displayed correctly   | Medium   |        |               |        |       |

---

### TC-010 — Checkout

| ID        | Test Case                                  | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ------------------------------------------ | -------- | ------ | ------------- | ------ | ----- |
| TC-010-01 | Checkout page opens correctly              | Critical |        |               |        |       |
| TC-010-02 | Required checkout fields are displayed     | High     |        |               |        |       |
| TC-010-03 | Valid customer information is accepted     | Critical |        |               |        |       |
| TC-010-04 | Order summary contains correct information | Critical |        |               |        |       |
| TC-010-05 | Order can be submitted with valid data     | Critical |        |               |        |       |

---

### TC-011 — Input Validation

| ID        | Test Case                                        | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ------------------------------------------------ | -------- | ------ | ------------- | ------ | ----- |
| TC-011-01 | Required fields cannot be submitted empty        | High     |        |               |        |       |
| TC-011-02 | Invalid phone number is handled correctly        | High     |        |               |        |       |
| TC-011-03 | Invalid input is rejected or validated           | High     |        |               |        |       |
| TC-011-04 | Validation messages are clear and understandable | Medium   |        |               |        |       |

---

### TC-012 — Responsive Design

| ID        | Test Case                                         | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | ------------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-012-01 | Homepage works correctly on mobile viewport       | High     |        |               |        |       |
| TC-012-02 | Catalog works correctly on mobile viewport        | High     |        |               |        |       |
| TC-012-03 | Product details work correctly on mobile viewport | High     |        |               |        |       |
| TC-012-04 | Cart works correctly on mobile viewport           | High     |        |               |        |       |
| TC-012-05 | No major layout issues appear on smaller screens  | Medium   |        |               |        |       |

---

### TC-013 — UI and Usability

| ID        | Test Case                                                | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | -------------------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-013-01 | Buttons and interactive elements are visible             | Medium   |        |               |        |       |
| TC-013-02 | Text is readable and not incorrectly truncated           | Medium   |        |               |        |       |
| TC-013-03 | Product cards have consistent layout                     | Low      |        |               |        |       |
| TC-013-04 | Interactive elements provide appropriate visual feedback | Medium   |        |               |        |       |

---

### TC-014 — Error Handling

| ID        | Test Case                                                | Priority | Status | Actual Result | Bug ID | Notes |
| --------- | -------------------------------------------------------- | -------- | ------ | ------------- | ------ | ----- |
| TC-014-01 | Application handles unavailable products correctly       | High     |        |               |        |       |
| TC-014-02 | Application handles invalid user input correctly         | High     |        |               |        |       |
| TC-014-03 | Application does not break after unexpected user actions | Medium   |        |               |        |       |
| TC-014-04 | Error messages are understandable                        | Medium   |        |               |        |       |

---

## 4. Environment

| Parameter           | Value         |
| ------------------- | ------------- |
| Operating System    | Windows 11    |
| Browser             | Google Chrome |
| Browser Version     |               |
| Screen Resolution   |               |
| Viewport Size       |               |
| Internet Connection |               |
| Test Date           |               |

---

## 5. Execution Notes

Use this section for observations that are important during testing but do not necessarily represent defects.

| Date | Test Case | Observation |
| ---- | --------- | ----------- |
|      |           |             |
|      |           |             |
|      |           |             |

---

## 6. Defect Summary

| Bug ID  | Test Case | Severity | Priority | Status | Description |
| ------- | --------- | -------- | -------- | ------ | ----------- |
| BUG-001 |           |          |          | Open   |             |
| BUG-002 |           |          |          | Open   |             |
| BUG-003 |           |          |          | Open   |             |

> Only add a bug to this table after the failed behavior has been investigated and confirmed as a defect.

---

## 7. Final Execution Summary

### Overall Result

**Execution Status:** In Progress

**Total Executed:** —

**Passed:** —

**Failed:** —

**Blocked:** —

**Not Run:** —

### Key Findings

* —
* —
* —

### Critical Issues

* —

### Recommendations

* —
* —
* —

---

## 8. Execution History

| Execution    | Date | Scope | Result |
| ------------ | ---- | ----- | ------ |
| Execution #1 |      |       |        |
| Execution #2 |      |       |        |
| Execution #3 |      |       |        |
