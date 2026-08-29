# Test Cases — Samurai Web Application

## 1. Test Case Overview

This document contains manual test cases for the Samurai food delivery web application.

The test cases cover the main user flows and critical application functionality, including navigation, product catalog, product details, shopping cart, ordering, validation, responsive behavior and UI.

### Test Case Index

| ID     | Test                        | Priority |
| ------ | --------------------------- | -------- |
| TC-001 | Homepage                    | High     |
| TC-002 | Navigation                  | High     |
| TC-003 | Product Catalog             | High     |
| TC-004 | Product Details             | High     |
| TC-005 | Search                      | High     |
| TC-006 | Shopping Cart               | Critical |
| TC-007 | Product Quantity Management | High     |
| TC-008 | Pricing and Discounts       | Critical |
| TC-009 | Delivery and Pickup         | Critical |
| TC-010 | Checkout                    | Critical |
| TC-011 | Input Validation            | High     |
| TC-012 | Responsive Design           | Medium   |
| TC-013 | UI and Usability            | Medium   |
| TC-014 | Error Handling              | High     |

---

# 2. Detailed Test Cases

## TC-001 — Homepage

### TC-001-01 — Verify homepage loading

**Priority:** High
**Type:** Functional

**Preconditions:**

* The website is accessible.
* The user has an active internet connection.

**Steps:**

1. Open the Samurai website.
2. Wait until the page finishes loading.
3. Observe the homepage.

**Expected Result:**

The homepage loads successfully and the main page elements are displayed without critical errors.

---

### TC-001-02 — Verify homepage navigation elements

**Priority:** High
**Type:** Functional

**Steps:**

1. Open the homepage.
2. Identify the main navigation elements.
3. Click each available navigation element.

**Expected Result:**

Each navigation element opens the corresponding page or section.

---

### TC-001-03 — Verify promotional content

**Priority:** Medium
**Type:** Functional / UI

**Steps:**

1. Open the homepage.
2. Review promotional banners and promotional sections.
3. Click available promotional links or buttons.

**Expected Result:**

Promotional content is displayed correctly and interactive elements lead to the corresponding content.

---

### TC-001-04 — Verify restaurant information

**Priority:** Medium
**Type:** UI / Functional

**Steps:**

1. Open the homepage.
2. Locate restaurant information.
3. Verify displayed working hours and contact information.

**Expected Result:**

Restaurant information is displayed clearly and consistently.

---

# TC-002 — Navigation

### TC-002-01 — Verify category navigation

**Priority:** High
**Type:** Functional

**Steps:**

1. Open the website.
2. Select a product category.
3. Observe the displayed content.

**Expected Result:**

The selected category opens and displays the corresponding products.

---

### TC-002-02 — Verify navigation back to homepage

**Priority:** Medium
**Type:** Functional

**Steps:**

1. Open any product category.
2. Navigate back to the homepage using the available navigation element.

**Expected Result:**

The homepage opens successfully.

---

### TC-002-03 — Verify navigation consistency

**Priority:** Medium
**Type:** UI

**Steps:**

1. Open several different sections of the website.
2. Compare the navigation elements.

**Expected Result:**

Navigation elements remain consistent and usable across the website.

---

# TC-003 — Product Catalog

### TC-003-01 — Verify product list display

**Priority:** High
**Type:** Functional

**Steps:**

1. Open a product category.
2. Observe the product list.

**Expected Result:**

Products belonging to the selected category are displayed.

---

### TC-003-02 — Verify product card information

**Priority:** High
**Type:** Functional / UI

**Steps:**

1. Open a product category.
2. Select several product cards.
3. Review the displayed information.

**Expected Result:**

Each product card displays the relevant product name, image, price and other available information correctly.

---

### TC-003-03 — Verify product images

**Priority:** High
**Type:** UI

**Steps:**

1. Open a product category.
2. Review product images.
3. Reload the page.
4. Review the images again.

**Expected Result:**

Product images load correctly and are displayed without broken-image placeholders or visual defects.

---

### TC-003-04 — Verify unavailable products

**Priority:** High
**Type:** Functional

**Steps:**

1. Open a category containing an unavailable product.
2. Review the product status.
3. Attempt to interact with the unavailable product.

**Expected Result:**

The application clearly indicates that the product is unavailable and prevents actions that should not be possible.

---

### TC-003-05 — Verify category switching

**Priority:** High
**Type:** Functional

**Steps:**

1. Open a product category.
2. Select another category.
3. Observe the displayed products.

**Expected Result:**

Products from the previously selected category are replaced with products from the new category.

---

# TC-004 — Product Details

### TC-004-01 — Verify product details

**Priority:** High
**Type:** Functional

**Steps:**

1. Open a product.
2. Review the product details.

**Expected Result:**

The product page displays the correct product information, including name, image, description and price where applicable.

---

### TC-004-02 — Verify product price consistency

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Open a product.
2. Note its displayed price.
3. Add the product to the cart.
4. Open the cart.
5. Compare the product price.

**Expected Result:**

The price displayed in the product interface matches the price displayed in the shopping cart.

---

### TC-004-03 — Verify product selection options

**Priority:** High
**Type:** Functional

**Steps:**

1. Open a product that contains configurable options.
2. Review the available options.
3. Select different options.
4. Observe the product information and price.

**Expected Result:**

Available options can be selected and the product information and price are updated according to the selected configuration.

---

# TC-005 — Search

### TC-005-01 — Verify search with valid input

**Priority:** High
**Type:** Functional

**Steps:**

1. Open the search functionality.
2. Enter the name of an existing product.
3. Submit the search.

**Expected Result:**

Relevant products matching the search query are displayed.

---

### TC-005-02 — Verify search with invalid input

**Priority:** Medium
**Type:** Negative

**Steps:**

1. Open the search functionality.
2. Enter a query that does not match any product.
3. Submit the search.

**Expected Result:**

The application clearly indicates that no matching products were found.

---

### TC-005-03 — Verify empty search query

**Priority:** Medium
**Type:** Negative

**Steps:**

1. Open the search functionality.
2. Leave the search field empty.
3. Submit the search.

**Expected Result:**

The application handles an empty search query correctly without errors.

---

# TC-006 — Shopping Cart

### TC-006-01 — Add a product to the cart

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Open an available product.
2. Add the product to the cart.
3. Open the shopping cart.

**Expected Result:**

The selected product appears in the shopping cart with the correct information and price.

---

### TC-006-02 — Add multiple products to the cart

**Priority:** High
**Type:** Functional

**Steps:**

1. Add one product to the cart.
2. Return to the catalog.
3. Add another product.
4. Open the cart.

**Expected Result:**

Both products are displayed in the shopping cart.

---

### TC-006-03 — Remove a product from the cart

**Priority:** High
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Open the shopping cart.
3. Remove the product.

**Expected Result:**

The product is removed from the cart and the cart total is recalculated correctly.

---

### TC-006-04 — Verify empty cart

**Priority:** High
**Type:** Functional

**Steps:**

1. Open the shopping cart with no products.

**Expected Result:**

The application displays an appropriate empty-cart state.

---

### TC-006-05 — Verify cart persistence during navigation

**Priority:** High
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Navigate to another section of the website.
3. Return to the shopping cart.

**Expected Result:**

The previously added product remains in the cart.

---

# TC-007 — Product Quantity Management

### TC-007-01 — Increase product quantity

**Priority:** High
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Increase its quantity by one.

**Expected Result:**

The product quantity increases by one and the total price is recalculated correctly.

---

### TC-007-02 — Decrease product quantity

**Priority:** High
**Type:** Functional

**Steps:**

1. Add multiple units of a product to the cart.
2. Decrease its quantity by one.

**Expected Result:**

The product quantity decreases by one and the total price is recalculated correctly.

---

### TC-007-03 — Verify minimum product quantity

**Priority:** High
**Type:** Boundary / Negative

**Steps:**

1. Add one product to the cart.
2. Attempt to decrease its quantity below the minimum allowed value.

**Expected Result:**

The application prevents an invalid quantity or removes the product according to the defined behavior.

---

### TC-007-04 — Verify quantity limit

**Priority:** Medium
**Type:** Boundary

**Steps:**

1. Add a product to the cart.
2. Increase its quantity repeatedly.
3. Observe the application's behavior when a maximum quantity is reached, if such a limit exists.

**Expected Result:**

The application prevents quantities exceeding the defined limit or handles the situation correctly.

---

# TC-008 — Pricing and Discounts

### TC-008-01 — Verify product price calculation

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Note its unit price and quantity.
3. Compare the calculated subtotal with the expected value.

**Expected Result:**

The subtotal equals the product price multiplied by the selected quantity.

---

### TC-008-02 — Verify total cart calculation

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Add multiple products to the cart.
2. Calculate the expected total manually.
3. Compare it with the cart total.

**Expected Result:**

The cart total is calculated correctly.

---

### TC-008-03 — Verify discounted product price

**Priority:** High
**Type:** Functional

**Steps:**

1. Open a product with a discount.
2. Compare the original and discounted prices.
3. Add the product to the cart.
4. Verify the price in the cart.

**Expected Result:**

The discounted price is calculated and displayed correctly throughout the user flow.

---

### TC-008-04 — Verify price recalculation after quantity change

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Increase its quantity.
3. Decrease its quantity.
4. Observe the total price after each change.

**Expected Result:**

The total price is recalculated correctly after every quantity change.

---

# TC-009 — Delivery and Pickup

### TC-009-01 — Verify delivery option

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Proceed to checkout.
3. Select delivery.

**Expected Result:**

The delivery option can be selected and the application displays the required delivery information.

---

### TC-009-02 — Verify pickup option

**Priority:** High
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Proceed to checkout.
3. Select pickup.

**Expected Result:**

The pickup option can be selected and the application displays the relevant information.

---

### TC-009-03 — Verify delivery address input

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Select delivery.
2. Enter a valid delivery address.
3. Continue the ordering process.

**Expected Result:**

The address is accepted and the user can continue the ordering process.

---

### TC-009-04 — Verify invalid delivery address

**Priority:** High
**Type:** Negative

**Steps:**

1. Select delivery.
2. Enter invalid or incomplete address information.
3. Attempt to continue.

**Expected Result:**

The application validates the address information and provides appropriate feedback.

---

# TC-010 — Checkout

### TC-010-01 — Open checkout with a valid cart

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Add an available product to the cart.
2. Open the cart.
3. Proceed to checkout.

**Expected Result:**

The checkout page opens successfully and displays the relevant order information.

---

### TC-010-02 — Verify required checkout fields

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Open the checkout page.
2. Review the available input fields.
3. Identify required fields.

**Expected Result:**

Required fields are clearly indicated.

---

### TC-010-03 — Submit checkout with empty required fields

**Priority:** Critical
**Type:** Negative

**Steps:**

1. Open the checkout page.
2. Leave required fields empty.
3. Attempt to submit the order.

**Expected Result:**

The application prevents submission and displays appropriate validation messages.

---

### TC-010-04 — Verify order summary

**Priority:** Critical
**Type:** Functional

**Steps:**

1. Add one or more products to the cart.
2. Proceed to checkout.
3. Review the order summary.

**Expected Result:**

The order summary contains the correct products, quantities, prices and total amount.

---

### TC-010-05 — Verify checkout after changing cart contents

**Priority:** High
**Type:** Functional

**Steps:**

1. Add a product to the cart.
2. Open checkout.
3. Return to the cart.
4. Change the product quantity.
5. Return to checkout.

**Expected Result:**

The checkout information reflects the updated cart contents and total price.

---

# TC-011 — Input Validation

### TC-011-01 — Verify valid customer information

**Priority:** High
**Type:** Functional

**Steps:**

1. Open the checkout form.
2. Enter valid customer information.
3. Continue the ordering process.

**Expected Result:**

Valid information is accepted.

---

### TC-011-02 — Verify empty required fields

**Priority:** High
**Type:** Negative

**Steps:**

1. Open a form containing required fields.
2. Leave one or more required fields empty.
3. Attempt to continue.

**Expected Result:**

The application prevents continuation and clearly identifies the invalid or missing fields.

---

### TC-011-03 — Verify invalid characters in input fields

**Priority:** Medium
**Type:** Negative

**Steps:**

1. Open the relevant form.
2. Enter invalid characters or an invalid format.
3. Attempt to continue.

**Expected Result:**

The application validates the input and provides appropriate feedback.

---

### TC-011-04 — Verify maximum input length

**Priority:** Medium
**Type:** Boundary

**Steps:**

1. Open a text input field.
2. Enter a value exceeding the expected maximum length.
3. Attempt to continue.

**Expected Result:**

The application prevents invalid input or handles the exceeded limit correctly.

---

# TC-012 — Responsive Design

### TC-012-01 — Verify desktop layout

**Priority:** High
**Type:** Responsive / UI

**Steps:**

1. Open the website on a desktop viewport.
2. Navigate through the main pages.
3. Observe the layout.

**Expected Result:**

The website is displayed correctly without overlapping, broken elements or unexpected horizontal scrolling.

---

### TC-012-02 — Verify tablet viewport

**Priority:** Medium
**Type:** Responsive / UI

**Steps:**

1. Open Chrome DevTools.
2. Enable responsive device mode.
3. Set a tablet-sized viewport.
4. Navigate through the website.

**Expected Result:**

The layout adapts correctly to the viewport size.

---

### TC-012-03 — Verify mobile viewport

**Priority:** High
**Type:** Responsive / UI

**Steps:**

1. Open Chrome DevTools.
2. Enable responsive device mode.
3. Set a mobile-sized viewport.
4. Navigate through the main pages.

**Expected Result:**

The website remains usable and all important content and controls are accessible.

---

### TC-012-04 — Verify shopping cart on mobile viewport

**Priority:** Critical
**Type:** Responsive / Functional

**Steps:**

1. Set a mobile viewport.
2. Add a product to the cart.
3. Open the cart.
4. Attempt to modify the cart.

**Expected Result:**

The shopping cart remains fully usable and its controls are accessible.

---

# TC-013 — UI and Usability

### TC-013-01 — Verify visual consistency

**Priority:** Medium
**Type:** UI

**Steps:**

1. Navigate through several pages.
2. Compare buttons, product cards, images, typography and spacing.

**Expected Result:**

Similar UI elements follow a consistent visual pattern throughout the application.

---

### TC-013-02 — Verify button states

**Priority:** Medium
**Type:** UI

**Steps:**

1. Locate interactive buttons.
2. Observe their default state.
3. Hover over buttons.
4. Click available buttons.

**Expected Result:**

Buttons provide appropriate visual feedback and their states are clearly distinguishable.

---

### TC-013-03 — Verify text readability

**Priority:** Medium
**Type:** Usability

**Steps:**

1. Navigate through the main pages.
2. Review headings, descriptions, prices and labels.

**Expected Result:**

Text is readable, properly positioned and does not overlap other interface elements.

---

# TC-014 — Error Handling

### TC-014-01 — Verify behavior after page refresh

**Priority:** Medium
**Type:** Functional

**Steps:**

1. Open a product page or cart.
2. Refresh the page.
3. Observe the application state.

**Expected Result:**

The application handles the page refresh correctly without unexpected errors or data loss that should not occur.

---

### TC-014-02 — Verify behavior during network interruption

**Priority:** High
**Type:** Negative / Network

**Steps:**

1. Open Chrome DevTools.
2. Open the Network panel.
3. Simulate an offline connection.
4. Attempt to interact with the application.

**Expected Result:**

The application handles the network interruption gracefully and provides appropriate feedback to the user.

---

### TC-014-03 — Verify browser console errors

**Priority:** Medium
**Type:** Technical

**Steps:**

1. Open Chrome DevTools.
2. Open the Console panel.
3. Navigate through the main website functionality.
4. Observe the console.

**Expected Result:**

No unexpected critical JavaScript errors are generated during normal user interaction.

---

# 3. Test Case Execution

Test execution results will be recorded after the test cases have been executed.

| Status     | Description                                        |
| ---------- | -------------------------------------------------- |
| PASS       | Actual result matches the expected result          |
| FAIL       | Actual result does not match the expected result   |
| BLOCKED    | Test cannot be executed due to an external blocker |
| NOT TESTED | Test has not yet been executed                     |

Detailed execution results will be documented in the [Test Execution Report](../test-execution/test-execution.md).

---

# 4. Defect Reporting

If a test case fails, the discovered defect will be documented separately in the `bug-reports` directory.

Each defect will contain:

* Bug ID
* Title
* Severity
* Priority
* Environment
* Preconditions
* Steps to reproduce
* Expected result
* Actual result
* Evidence

A failed test case does not automatically mean that the application contains a defect. The observed behavior must first be investigated and compared with the expected behavior or available business rules.

---

# 5. Notes

Test cases may be updated during the testing process if new functionality, business rules or important user scenarios are discovered.

The final set of test cases will reflect the actual functionality available in the application at the time of testing.
