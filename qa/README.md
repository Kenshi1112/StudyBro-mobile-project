# QA / Test Report — StudyBro

This directory contains manual QA work performed on the StudyBro app as independent practice for a Software Testing / QA job application portfolio.

The testing was conducted after the original project was completed and is not part of the original course assignment.

## Scope

Manual functional testing covering the main features of the app:

- Login / Register
- Profile
- Timetable
- Planner
- Dashboard

## What's Inside

| File | Contents |
| --- | --- |
| `test-cases/Test_Report.xlsx` | Contains 3 sheets: TS (Test Suites), TC (Test Cases), and Bug Report |

- **TS** — High-level grouping of test cases by feature area
- **TC** — Detailed test cases including steps, expected result, actual result, and test status
- **Bug Report** — Defects found during testing, including severity and reproduction steps

## Summary

- Total test cases: 59
- Passed: 49
- Failed: 10
- Bugs logged: 5 (1 High, 3 Medium, 1 Low)

Breakdown by screen: Register (13), Login (7), Profile (9), Timetable (15), Planner (10), Dashboard (5)

## Testing Approach

- Manual functional testing
- Exploratory testing
- Equivalence Partitioning (EP)
- Boundary Value Analysis (BVA)

## Testing Tools

- Android Studio Emulator
- Firebase Console
- Microsoft Excel
