# Woocommerce_QA_Project
Pams-Store QA Testing Project

QA testing engagement for Pams-Store, a WooCommerce demo e-commerce site, performed as a portfolio project to demonstrate manual QA testing skills across the full test lifecycle — test planning, test case design, execution, defect logging, and reporting.

🔗 Live demo site: https://pams-store.42web.io

About This Project

This repository documents a complete manual QA testing cycle on a WooCommerce-based demo store using the Storefront theme. The goal was to validate core e-commerce functionality end-to-end — from user registration through checkout and order management — using structured test cases, exploratory testing, and formal defect reporting.

Role: QA Lead — Ilori Sunday Ezekiel


Repository Structure

First-Project-Pams/
│
├── README.md
│
├── Test-Plan/
│   └── WooCommerce_Test_Plan.docx
│
├── Test-Cases/
│   ├── M1_Authentication_Test_Cases.csv
│   ├── M2_Product_Catalog_Test_Cases.csv
│   ├── M3_Search_Filtering_Test_Cases.csv
│   ├── M4_Shopping_Cart_Test_Cases.csv
│   ├── M5_Checkout_Test_Cases.csv
│   └── M6_Order_Management_Test_Cases.csv
│
├── Bug-Report/
│   ├── Pams_Store_Bug_Report.docx
│   └── Pams_Store_Bug_Report.csv
│
└── Test-Summary/
    └── Pams_Store_Test_Summary_Report.docx


Scope

Testing covered six functional milestones:

MilestoneAreaTest CasesM1Authentication24M2Product Catalog23M3Search & Filtering18M4Shopping Cart25M5Checkout38M6Order Management28Total156

UI/UX issues found during testing were logged directly in the bug report rather than tracked as separate test cases, since the site uses the standard WooCommerce Storefront theme. Regression testing was out of scope, as this is a static demo environment with no active development cycle.


Results Summary


156 test cases executed
149 passed
6 failed (logged as defects)
1 blocked/skipped (environment limitation, not a defect)
12 defects logged: 1 Critical, 1 High, 8 Medium, 2 Low



Repository Contents

FileDescriptionTest-Plan/WooCommerce_Test_Plan.docxTest strategy, scope, milestones, entry/exit criteria, risk assessment, and defect classificationTest-Cases/M1_Authentication_Test_Cases.csv24 test cases covering registration, login, logout, and password resetTest-Cases/M2_Product_Catalog_Test_Cases.csv23 test cases covering product listing, pagination, and product detail pagesTest-Cases/M3_Search_Filtering_Test_Cases.csv18 test cases covering search and sorting functionalityTest-Cases/M4_Shopping_Cart_Test_Cases.csv25 test cases covering cart operations, quantity controls, and couponsTest-Cases/M5_Checkout_Test_Cases.csv38 test cases covering guest/logged-in checkout, shipping, coupons, and order confirmationTest-Cases/M6_Order_Management_Test_Cases.csv28 test cases covering order history and order detail viewsBug-Report/Pams_Store_Bug_Report.docxFormal bug report with full defect details grouped by categoryBug-Report/Pams_Store_Bug_Report.csvBug report in spreadsheet format for Google Sheets importTest-Summary/Pams_Store_Test_Summary_Report.docxFinal summary of test execution results, defect breakdown, and risk assessment


Tools & Method


Manual exploratory and scripted testing
Browser: Google Chrome (latest)
OS: Windows
Test case and defect tracking via Google Sheets
Reports compiled in Word/CSV format for portfolio presentation



Notes

This is a demo/training environment, not a production application. Some logged issues (e.g. placeholder description text, a broken external swag-store link) stem from WooCommerce demo sample data rather than functional defects in the store itself, and are flagged as such in the bug report.
