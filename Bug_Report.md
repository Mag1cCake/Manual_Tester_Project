# Bug Report

## Bug ID
TC-T-02

## Title
Inconsistent balance rounding across application screens

## Environment
- Platform: Android
- OS Version: Android 15
- Device: Realme GT6 (physical device)
- Aplication Version: 1.8.10

## Preconditions
- User is logged in
- Initial setup is completed
- Account balance is 1000

## Steps to Reproduce
1. Add an income transaction with amount 100.50
2. Observe account balance on main screen
3. Open account edit screen

## Actual Result
- Main screen displays balance as 1101
- Edit account screen displays balance as 1100.50

## Expected Result
- Account balance should display the exact calculated value including decimals on all screens
- No automatic rounding should be applied without user configuration

## Severity
Medium

## Priority
Medium

## Status
Open