# Test Plan

Overview
- Project: Pams Store (Woocommerce_QA_Project)
- Purpose: Define scope, objectives, approach and schedule for QA activities.

Scope
- In-scope: core shopping flow (browse, add to cart, checkout), account management, product search, and payments (sandbox).
- Out-of-scope: 3rd-party payment gateway live transactions, performance/stress testing (unless requested).

Objectives
- Verify critical user journeys work end-to-end.
- Identify and document defects with clear repro steps and screenshots.
- Provide a test execution summary with pass/fail status and open issues.

Test approach
- Manual test execution using the Test Cases in docs/Test-Cases.
- Automated regression tests stored under Pams-Store/tests/ (optional).

Entry criteria
- Test environment is available and stable.
- Test data is prepared.
- Build/deployment to test environment completed.

Exit criteria
- All high severity defects resolved or accepted by stakeholders.
- Test execution completed and summary published.

Environment
- Staging URL: <replace-with-staging-url>
- Browser(s): Chrome (latest), Firefox (latest)
- Test accounts: <list test accounts>

Schedule
- Start date: <YYYY-MM-DD>
- End date: <YYYY-MM-DD>

Roles and responsibilities
- QA Lead: <name>
- Testers: <names>
- Developers: <names>

Notes
- Update this file with any scope or schedule changes.
