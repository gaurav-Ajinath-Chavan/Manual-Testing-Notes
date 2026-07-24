# Testing Types

## Smoke Testing

### Definition
Smoke Testing is performed to verify whether the critical functionalities of the application are working after a new build is received.

### Purpose
- Verify build stability
- Ensure major functionalities work
- Decide whether further testing can continue

### Example
Check if the application launches successfully and the login feature works.

---

## Sanity Testing

### Definition
Sanity Testing is performed after minor changes or bug fixes to verify that the specific functionality works correctly.

### Purpose
- Validate recent changes
- Ensure bug fixes are working
- Avoid full regression testing

### Example
After fixing the password reset feature, test only the password reset functionality.

---

## Regression Testing

### Definition
Regression Testing ensures that recent code changes have not affected the existing functionalities.

### Purpose
- Verify existing features still work
- Detect unintended side effects
- Maintain software stability

### Example
After adding a new payment option, verify that login, registration, and order placement still work correctly.

---

## Retesting

### Definition
Retesting is performed to verify that a reported defect has been fixed successfully.

### Purpose
- Confirm the defect is resolved
- Execute only the failed test cases related to the bug

### Example
Verify that the login page works correctly after the login bug has been fixed.

---

## Functional Testing

### Definition
Functional Testing verifies that each feature of the application works according to the specified requirements.

### Examples
- Login Testing
- Registration Testing
- Search Functionality
- Payment Processing

---

## Non-Functional Testing

### Definition
Non-Functional Testing verifies aspects of the application other than functionality.

### Types
- Performance Testing
- Load Testing
- Stress Testing
- Security Testing
- Usability Testing
- Compatibility Testing
- Reliability Testing

---

# Difference Between Functional and Non-Functional Testing

| Functional Testing | Non-Functional Testing |
|--------------------|------------------------|
| Tests application features | Tests application quality attributes |
| Validates business requirements | Validates performance, security, usability, etc. |
| Focuses on "What" the system does | Focuses on "How well" the system performs |
