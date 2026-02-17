---
name: Update an Account
about: Update an existing account to keep records accurate.
title: 'User Story: Update an Account in the Service'
labels: user-story
---

**As a** Admin
**I need** to update an existing account
**So that** I can keep records accurate

### Details and Assumptions
* The service exposes a REST API with PUT method support
* Only existing accounts can be updated
* The request body contains the updated account fields in JSON format

### Acceptance Criteria
```gherkin
Given ID 10 exists in the database
When I send a PUT request to /accounts/10 with updated data
Then the account in the database is updated accordingly
```
