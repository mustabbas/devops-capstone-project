---
name: Read an Account
about: Retrieve a specific account by its ID from the service.
title: 'User Story: Read an Account from the Service'
labels: user-story
---

**As a** User
**I need** to be able to retrieve a specific account by its ID
**So that** I can view the account details

### Details and Assumptions
* The service exposes a REST API
* Accounts are identified by a unique numeric ID
* The response format is JSON

### Acceptance Criteria
```gherkin
Given ID 5 exists in the database
When I send a GET request to /accounts/5
Then I receive a 200 OK status code and the account data in JSON format
```
