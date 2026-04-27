# Bykea-Ride-Testing
This repository contains manual testing documentation for the Bykea Ride module, including positive and negative test cases, functional, usability, performance, and validation testing. It also includes identified bugs, test scenarios, and detailed execution results for quality assurance purposes.

## Project Overview

This repository contains manual testing artifacts for the Bykea Ride Module. The objective is to ensure the quality, reliability, and functionality of the ride booking flow through structured Software Quality Assurance (SQA) practices.

### Testing includes:
Functional Testing, System Testing, Usability Testing, Negative & Positive Test Scenarios, Validation Testing and Basic Performance Observations

### Test Coverage
The following areas of the Ride Module are covered:
1. Ride Booking Flow
2. Pickup & Drop Location Selection
3. Vehicle Selection
4. Fare Estimation
5. Ride Confirmation
6. Ride Cancellation

# Bug Identified
🔴 Bug: Ride booking allowed despite same pickup and drop location validation warning

 #### Description:
The system displays a warning message when the pickup and drop locations are the same or too close. However, it still allows the user to proceed and find/book a ride, which indicates a validation inconsistency issue.

#### Expected Result:
The system should block ride booking when invalid or same pickup and drop locations are entered.

#### Actual Result:
A warning message is shown, but the system still allows the user to proceed with ride booking.

### ⚖️ Bug Severity & Priority
Severity: Medium
(Does not crash the system but affects business logic and validation integrity)
Priority: High
(Core ride booking flow is impacted and may lead to incorrect bookings)

## Conclusion
This testing activity ensures that the Ride Booking Module is analyzed under different scenarios to detect functional inconsistencies and improve overall system quality. Further end-to-end testing is recommended for complete system validation.

##### Note: Screenshots of test execution and bug reproduction are attached in the repository under relevant test cases.
