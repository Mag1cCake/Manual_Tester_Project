# Test Plan

## 1. Introduction
This test plan describes the testing activities for a mobile finance application.
The goal of testing is to verify registration, core functionality, data accuracy, and stability of the application.

## 2. Scope

### In Scope
- User registration
- User authentication
- Account management
- Transactions
- Statistics and reports
- Data persistence
- Basic non-functional testing

### Out of Scope
- Performance testing
- Security testing
- Backend and API testing

## 3. Test Objects
- User authentication (registration, login, logout)
- Accounts
- Transactions
- Statistics
- Application lifecycle (restart, background, login)

## 4. Test Approach
Manual functional testing was performed based on predefined test cases.
Authentication flows were tested to ensure successful user access to the application.
Positive, negative, and boundary value testing techniques were used.
Testing was executed on a real Android device.

## 5. Test Environment
- Platform: Android
- OS Version: Android 15
- Device: Realme GT6 (physical device)
- Aplication Version: 1.8.10
- Network: Wi-Fi

## 6. Entry & Exit Criteria

### Entry Criteria
- Application is installed
- User account is created
- User is logged in
- Initial setup is completed

### Exit Criteria
- All planned test cases are executed
- All critical and major defects are reported
- No critical defects remain open

## 7. Deliverables
- Test plan
- Test cases
- Bug reports
- README documentation

## 8. Risks & Assumptions
- Balance rounding may affect user trust
- Testing is limited to a single platform and device