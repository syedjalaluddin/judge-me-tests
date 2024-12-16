# Empty branch for PR
### Summary
This PR adds an automated Cypress test suite and GitHub Actions CI/CD pipeline for the Judge.me reviews site.

### Changes Made
1. Set up Cypress with high-priority test cases.
2. Integrated GitHub Actions for CI/CD, running tests on every push and pull request.
3. Configured automated artifact upload for test failure reports.

### How to Review
- Switch to the `feature/cypress-tests` branch to explore the implementation.
- View the test plan in `TEST_PLAN.md`.
- Review the GitHub Actions workflow in `.github/workflows/cypress.yml`.

### Next Steps
1. Expand the test suite to include performance and accessibility tests.
2. Parallelize tests for better efficiency.

### Notes
This PR is raised against the `empty-branch` as per the requirements. Please review and provide feedback!
