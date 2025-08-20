✅ Code Review Checklist
Code Quality

 Code follows agreed naming conventions and style guide.

 Code is readable and maintainable (clear variables, functions, classes).

 No unnecessary complexity (e.g., duplicated code, overly nested logic).

 Comments are meaningful (explain why, not what).

Testing

 Unit tests are included and cover edge cases.

 Integration/functional tests are updated if needed.

 Tests pass locally and in CI/CD pipeline.

 Negative scenarios (error handling, nulls, invalid input) are tested.

Correctness

 Code meets the acceptance criteria in the user story.

 All functionality works as described.

 No breaking changes introduced (backward compatibility checked).

Performance & Security

 Code avoids obvious performance bottlenecks.

 Sensitive data is handled securely (no hardcoded secrets, passwords, tokens).

 Input validation is in place.

 Dependencies are safe (no known vulnerabilities).

✅ QA / Delivery Checklist
Automated QA

 Static analysis (e.g., SonarQube, ESLint, StyleCop) passes with no new issues.

 Build runs cleanly without warnings.

 Automated tests (unit, integration, regression) are green in CI/CD.

 Code coverage thresholds are met.

Manual QA

 Feature has been tested against acceptance criteria.

 Exploratory testing done for edge cases.

 User experience (UI/UX) aligns with design specs.

 Cross-browser/device testing (if applicable).

 Accessibility checks applied (if required by product).

Team Delivery Integration

 PR linked to the correct user story/issue.

 Documentation updated (API docs, README, release notes if needed).

 Monitoring/logging considerations included.

 Deployment verified in the test/staging environment.

 Feedback gathered during sprint review/demo.
