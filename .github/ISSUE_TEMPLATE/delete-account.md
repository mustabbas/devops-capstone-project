---
name: Delete an Account
about: Remove an account from the service to comply with privacy laws.
title: 'User Story: Delete an Account from the Service'
labels: user-story
---

**As a** Compliance Officer
**I need** to remove an account
**So that** we comply with privacy laws

### Details and Assumptions
* The service exposes a REST API with DELETE method support
* Deleting an account permanently removes it from the database
* A 204 No Content response is returned on successful deletion

### Acceptance Criteria
```gherkin
Given ID 7 exists in the database
When I send a DELETE request to /accounts/7
Then the account is removed from the database
```
