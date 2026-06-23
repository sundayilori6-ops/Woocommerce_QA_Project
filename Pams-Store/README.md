# Pams Store

# Woocommerce_QA_Project
Pams-Store QA Testing Project

QA testing engagement for Pams-Store, a WooCommerce demo e-commerce site, performed as a portfolio project to demonstrate manual QA testing skills across the full test lifecycle — test planning, test case design and execution, defect reporting, and test-summary reporting.

🔗 Live demo site: https://pams-store.42web.io

## About This Project

This repository documents a complete manual QA testing cycle on a WooCommerce-based demo store using the Storefront theme. The goal was to validate core e-commerce functionality end-to-end — from user authentication and product discovery through checkout and order management. The work includes a formal test plan, organized test case artifacts, logged defects, and a final test summary for portfolio presentation.

Role: QA Lead — Ilori Sunday Ezekiel

---

## Repository structure

Woocommerce_QA_Project/
├── README.md
├── Test-Plan/
│   └── WooCommerce_Test_Plan.docx
├── Test-Cases/
│   ├── M1_Authentication_Test_Cases.csv
│   ├── M2_Product_Catalog_Test_Cases.csv
│   ├── M3_Search_Filtering_Test_Cases.csv
│   ├── M4_Shopping_Cart_Test_Cases.csv
│   ├── M5_Checkout_Test_Cases.csv
│   └── M6_Order_Management_Test_Cases.csv
├── Bug-Report/
│   ├── Pams_Store_Bug_Report.docx
│   └── Pams_Store_Bug_Report.csv
└── Test-Summary/
    └── Pams_Store_Test_Summary_Report.docx

---

## Scope

Testing covered six functional milestones. The table below summarizes areas and the number of test cases executed per milestone.

| Milestone | Area               | Test Cases |
|-----------|--------------------|------------|
| M1        | Authentication     | 24         |
| M2        | Product Catalog    | 23         |
| M3        | Search & Filtering | 18         |
| M4        | Shopping Cart      | 25         |
| M5        | Checkout           | 38         |
| M6        | Order Management   | 28         |
| **Total** |                    | **156**    |

UI/UX issues discovered during exploratory testing were logged in the bug report and classified along with functional defects.

---

## Results Summary

- 156 test cases executed
- 149 passed
- 6 failed (logged as defects)
- 1 blocked/skipped (environment limitation, not a defect)
- 12 defects logged: 1 Critical, 1 High, 8 Medium, 2 Low

---

## Repository Contents

| File path | Description |
|-----------|-------------|
| Test-Plan/WooCommerce_Test_Plan.docx | Test strategy and plan: scope, milestones, entry/exit criteria, risk assessment, and defect classification. |
| Test-Cases/M1_Authentication_Test_Cases.csv | Authentication test cases (24). |
| Test-Cases/M2_Product_Catalog_Test_Cases.csv | Product catalog test cases (23). |
| Test-Cases/M3_Search_Filtering_Test_Cases.csv | Search & filtering test cases (18). |
| Test-Cases/M4_Shopping_Cart_Test_Cases.csv | Shopping cart test cases (25). |
| Test-Cases/M5_Checkout_Test_Cases.csv | Checkout test cases (38). |
| Test-Cases/M6_Order_Management_Test_Cases.csv | Order management test cases (28). |
| Bug-Report/Pams_Store_Bug_Report.docx | Detailed bug report (Word) summarizing logged defects. |
| Bug-Report/Pams_Store_Bug_Report.csv | Bug report in CSV format for tracking defects. |
| Test-Summary/Pams_Store_Test_Summary_Report.docx | Final test summary report (Word) compiling results and findings. |

---

## Tools & Method

- Manual exploratory and scripted testing
- Browser: Google Chrome (latest)
- OS: Windows
- Test case and defect tracking via Google Sheets
- Reports compiled in Word/CSV format for portfolio presentation

---

## Notes

This is a demo/training environment, not a production application. Some logged issues (for example, placeholder content and a broken external swag-store link) stem from WooCommerce demo sample data rather than site customizations. Use the live demo link above to reproduce test scenarios where applicable.

If you'd like additional changes (for example: add a contributors section, link to individual test-case CSVs with sample rows, or export the repository tree as a file), tell me what to add and I will update the README accordingly.
