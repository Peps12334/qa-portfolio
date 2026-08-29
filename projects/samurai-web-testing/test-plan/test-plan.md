# Test Plan — Samurai Web Application

## 1. Document Information

| Field            | Value                      |
| ---------------- | -------------------------- |
| Project          | Samurai Web Application    |
| Document         | Test Plan                  |
| Testing Type     | Manual Testing             |
| Application Type | Web Application            |
| Environment      | Windows 11 / Google Chrome |
| Location         | Yaroslavl, Russia          |
| Status           | Draft                      |
| Author           | Artem                      |

---

## 2. Project Overview

Samurai is a food delivery web application serving customers in Yaroslavl.

The application allows users to browse the food catalog, view product information, select products, add them to a shopping cart and proceed through the ordering process.

The website contains multiple product categories, including rolls, sets, pizza, WOK dishes, soups, salads, snacks, desserts and drinks.

The application also provides different service modes, including delivery, pickup and ordering in the restaurant.

---

## 3. Testing Objectives

The primary objective of testing is to evaluate the quality, functionality and usability of the Samurai web application from an end-user perspective.

The testing objectives are:

* Verify that core user functionality works as expected.
* Verify that users can browse and interact with the product catalog.
* Verify that products can be added, modified and removed from the shopping cart.
* Verify the correctness of prices and product information.
* Verify the main ordering workflow.
* Verify validation and error handling.
* Identify functional defects and inconsistencies.
* Identify UI and usability issues.
* Check responsive behavior at different viewport sizes.
* Investigate selected issues using Chrome DevTools.
* Document reproducible defects using structured bug reports.

---

## 4. Scope

### 4.1 In Scope

#### Homepage

* Page loading
* Navigation
* Main categories
* Product previews
* Promotional content
* Working links
* Display of restaurant information
* Working hours information

#### Product Catalog

* Category navigation
* Product availability
* Product names
* Product descriptions
* Product images
* Product prices
* Discounted prices
* Product labels
* Product cards
* Product details
* Search functionality

#### Shopping Cart

* Adding products
* Removing products
* Changing product quantity
* Cart total calculation
* Product information in the cart
* Cart persistence during navigation
* Empty cart behavior

#### Ordering Flow

* Delivery mode
* Pickup mode
* Restaurant ordering mode
* Address input
* Order information
* Form validation
* Required fields
* Order total
* Navigation between ordering steps

#### UI and Usability

* Layout consistency
* Typography
* Image presentation
* Button states
* Interactive elements
* Error messages
* Visual feedback
* Content readability
* Navigation consistency

#### Responsive Testing

Testing will include different viewport sizes using Chrome DevTools.

The following areas will be evaluated:

* Layout adaptation
* Navigation
* Product cards
* Images
* Buttons
* Shopping cart
* Forms
* Text readability
* Horizontal scrolling
* Element overlapping

#### Browser and Network Investigation

Chrome DevTools will be used to investigate selected issues, including:

* Console errors
* HTTP status codes
* Failed network requests
* Image loading problems
* Request/response behavior
* Basic client-side errors

---

## 5. Out of Scope

The following areas are outside the scope of this project:

* Source code review
* Backend code testing
* Direct database testing
* Load and stress testing
* Full performance testing
* Penetration testing
* Security audit
* Payment provider testing outside the application's interface
* Testing of the native mobile application
* Testing on physical mobile devices

---

## 6. Testing Types

The following testing approaches will be applied during the project:

### Functional Testing

Verification that application functionality works according to its intended behavior.

### Exploratory Testing

Unscripted investigation of the application to discover unexpected behavior and potential defects.

### UI Testing

Verification of visual elements, layout, consistency and interaction states.

### Usability Testing

Evaluation of the application from the perspective of a typical end user.

### Responsive Testing

Verification of application behavior at different viewport sizes.

### Negative Testing

Verification of application behavior when users provide invalid, incomplete or unexpected input.

### Boundary Testing

Testing values at and around important limits, such as product quantities, order amounts and input field restrictions.

### Compatibility Testing

Basic verification of the application's behavior across supported browser configurations and viewport sizes available for testing.

### Smoke Testing

A short set of checks used to determine whether the main application functionality is operational before deeper testing.

### Regression Testing

Re-execution of previously failed or affected test scenarios after defects are fixed or application behavior changes.

---

## 7. Test Approach

Testing will be performed manually using a combination of predefined test cases, checklists and exploratory testing.

The testing process will consist of the following stages:

1. Application exploration
2. Identification of major user flows
3. Test planning
4. Test case and checklist preparation
5. Functional testing
6. UI and usability testing
7. Responsive testing
8. Exploratory testing
9. Defect documentation
10. Retesting of identified defects where possible
11. Regression testing of affected functionality
12. Test result analysis
13. Final test summary

---

## 8. Main User Flows

The following user flows will receive particular attention:

### Flow 1 — Browse Products

```text
Homepage
↓
Product Category
↓
Product Card
↓
Product Details
```

### Flow 2 — Add Product to Cart

```text
Product Catalog
↓
Select Product
↓
Add Product
↓
Open Cart
↓
Verify Product
```

### Flow 3 — Modify Cart

```text
Cart
↓
Increase Quantity
↓
Decrease Quantity
↓
Remove Product
↓
Verify Total
```

### Flow 4 — Place an Order

```text
Product
↓
Cart
↓
Checkout
↓
Select Delivery Method
↓
Enter Required Information
↓
Validate Order Data
↓
Place Order
```

### Flow 5 — Responsive Usage

```text
Open Website
↓
Change Viewport Size
↓
Navigate Through Website
↓
Interact With Products
↓
Open Cart
↓
Check Ordering Interface
```

---

## 9. Test Data

Test data will be generated specifically for testing purposes.

Examples include:

* Valid product selections
* Multiple product quantities
* Empty cart
* Invalid form values
* Empty required fields
* Boundary values
* Different viewport sizes
* Different product categories
* Available and unavailable products

Real customer information will not be used during testing.

---

## 10. Test Environment

### Hardware

Testing will be performed on a desktop computer.

### Operating System

Windows 11.

### Browser

Google Chrome.

### Browser Tools

Chrome DevTools will be used for:

* Console investigation
* Network investigation
* Responsive testing
* Basic request analysis

---

## 11. Defect Management

All reproducible defects identified during testing will be documented using individual bug reports.

Each bug report will contain:

* Bug ID
* Title
* Environment
* Preconditions
* Steps to reproduce
* Expected result
* Actual result
* Severity
* Priority
* Evidence
* Additional notes where necessary

Defects will be classified according to their impact on the application and the urgency of fixing them.

---

## 12. Entry Criteria

Testing can begin when:

* The application is accessible.
* The main website functionality is available.
* The testing environment is configured.
* The initial application exploration has been completed.
* The testing scope has been defined.

---

## 13. Exit Criteria

Testing will be considered complete when:

* All planned test scenarios within the defined scope have been executed.
* Identified critical user flows have been tested.
* Discovered reproducible defects have been documented.
* Major affected functionality has been retested where possible.
* Test results have been analyzed.
* A final Test Summary Report has been prepared.

---

## 14. Risks and Limitations

Potential risks and limitations include:

* Website functionality may change during the testing period.
* Some functionality may depend on restaurant working hours.
* Some ordering functionality may require real customer data or an actual order and therefore may not be fully testable.
* Some defects may be environment-specific.
* Backend behavior cannot be directly verified without access to server-side systems.
* The project does not include dedicated performance or security testing.

---

## 15. Deliverables

The following deliverables will be created as part of this project:

* Test Plan
* Test Cases
* Functional Checklist
* UI Checklist
* Responsive Checklist
* Bug Reports
* Test Execution Report
* Test Summary Report
* Screenshots and other test evidence

---

## 16. Project Status

**In Progress**

This Test Plan will be updated if the testing scope or application functionality changes significantly during the project.
