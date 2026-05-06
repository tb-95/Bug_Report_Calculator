# Bug Report – Calculator Application

## Project Overview
This repository contains a comprehensive QA audit of a **broken calculator application**. The goal was to identify, document, and classify functional defects, with a focus on real-world software testing scenarios. The project demonstrates skills in:

- Manual testing of a desktop application
- Creating structured bug reports (severity + priority)
- Using screen recordings and screenshots as attachments
- Testing across multiple input methods (on‑screen keypad + physical keyboard)

## Repository Structure
Bug_Report_Calculator/
├── Calculator_App/ # The test application (MyCalculatorv1.exe and dependencies)
├── Report/
│ ├── Bug_report_Bednar.pdf # Full bug report
│ └── screen_recordings/ # Video evidence for each bug
└── README.md

text

## Bug Report Summary
A complete **17‑page PDF** documenting **13 unique bugs**, classified by severity and priority.

| Bug ID | Severity | Priority | Description |
|--------|----------|----------|-------------|
| BUG‑001 | High | P1 | On‑screen keypad blocks three consecutive ‘9’ digits |
| BUG‑002 | High | P1 | Digit ‘7’ on on‑screen keypad is displayed as ‘4’ |
| BUG‑003 | High | P1 | Incorrect results for large operands (+, -, ×) |
| BUG‑003.4 | Critical | P0 | Division with large operand → application crash |
| BUG‑004 | Critical | P0 | Division by zero → application crash |
| BUG‑005 | Medium | P2 | ‘Enter’ key on physical keyboard does nothing |
| BUG‑006 | Medium | P2 | No validation of manually typed ‘=’ inside expression |
| BUG‑007 | Low | P3 | App launches with pre‑filled “1 + 1 = 2” |
| BUG‑008 | High | P1 | Second operand with 6+ identical digits → wrong result |
| BUG‑009 | High | P1 | Multiplication duplicates first digit of second operand |
| BUG‑010 | Medium | P2 | Long results are cut off (UI overflow) |
| BUG‑011 | High | P1 | Calculated result can be edited with Backspace/Delete |
| BUG‑012 | High | P1 | Result not recalculated after modifying expression |
| BUG‑013 | High | P1 | Cannot continue calculation using previous result |

## Methodology
- **Application**: `MyCalculatorv1.exe` (test build v1.0)
- **Platform**: Desktop
- **Testing techniques**:
  - Exploratory testing of all arithmetic operations
  - Boundary value analysis (large operands, zero division)
  - Input method comparison (on‑screen vs. physical keyboard)
- **Documentation**:
  - Every bug includes: Steps to Reproduce, Expected Result, Actual Result, Frequency, and Attachments (screenshots or screen recordings)

## How to Use
1. Download the `Calculator_App` folder.
2. Run `MyCalculatorv1.exe` (Windows only).
3. Refer to `Report/Bug_report_Bednar.pdf` for the full list of defects.

> ⚠️ **Note**: This is a test application intentionally built with defects. Use only for QA training or portfolio demonstration.

## Why This Project?
Potential employers can see:
- Structured, professional bug reporting
- Way of thinking
- Clear prioritisation (P0 = critical, P3 = low)
- Multi‑method testing (UI, keyboard, edge cases)
- Evidence‑based documentation (video + screenshots)

## Author
**Tomáš Bednář**  
[GitHub Profile](https://github.com/tb-95)
