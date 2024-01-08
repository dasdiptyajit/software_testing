---
title: Test levels and test types
updated: 2024-01-08 16:30:21Z
created: 2024-01-08 15:13:06Z
latitude: 49.48745920
longitude: 8.46603950
altitude: 0.0000
---

## Test levels
1. **Unit Testing:** Individual components/ units, verify each part performs as designed.  
- [ ] Challenges: Identifying edge cases, isolating dependencies.
2. **Integration Testing:**  Testing the combination of software units, verify each part performs as designed. (e.g. test interaction (front-backend) between authentication module and a database module). 
- [ ] Challenges: ensuring smoothing communication between modules, handling data inconsistencies.
3. **System Testing:** Testing the complete integrated system, verify the results meets specified requirements. Evaluate Functional & non-functional requirements. Test case: verify end-user completes all tasks. 
- [ ] Challenges: Comprehensive testing of all requirements, managing complex test scenarios.
4.  **Acceptance Testing:** Testing software for acceptability, helps to verify the system is ready for delivery and use. e.g., testing the user experience (UX) and overall performance of a mobile app before release to store. Test case: verify mobile app meets target audience needs, is user-friendly, reponsive and secure. 
- [ ] Challenges: Ensure software meets expectations of end-users, obtaining feedback from diverse groups. 
#

## Types of testing: functional and non-functional testing

-  **Functional:** testing is based on software functions and requirements. We test the app against its functional specifications. Ensures the software works as expected. Meet the needs of stakeholders and end-users. 

	**Objectives:**  Validating functions, requirements
- [ ] Validate software functions.
- [ ] Ensure conformance to requirements. 
- [ ] Verify user scenarios. e.g., login functionality, form submission, data retrieval 

-  **Non-functional:** testing software's non functional aspects: oerformance, usability and security
**Objectives:** Performance, usability, security
- [ ] ensures software not only works correctly but also performs optimally in range of scenarios. 
- [ ] includes: performance testing (response time, scalability:use of a lot users of the software at the same time), usability testing (user-friendlyness, end-user experience: feature testing), security testing (identifying vulnerabilities: protective user sensitive data, e.g., E2E).

#

## Static testing (early develpment process)
- Early identifying the issues
- Analysing code, documents and other artefacts
- No code executions

**Static testing technique includes**:
1. Code reviews: examine code, find errors, provide feedback
2. Walkthroughs: devs & testers discuss code & designs to find issues
3. Static code analysis tools: analyse code for common errors and potentials issues. This include: Automated tools, analyse code for errors, wild range of popular tools. 
#
## Static code analysis tools
- **usefulness:** early detection of issues, improved code quality, ensure proper documentation, faster development, automation issue idenfication, consistency across the project, enforce unify coding style, enganced security. 
- **Includes:**
1. SonarQube
2. ESLint
3. PYLint (python)
4. FindBugs (java)
5. PMD (java)