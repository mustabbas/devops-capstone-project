---
name: List All Accounts
about: Retrieve a list of all accounts for an overview of the user base.
title: 'User Story: List All Accounts in the Service'
labels: user-story
---

**As a** Manager
**I need** to see a list of every account
**So that** I can get an overview of the user base

### Details and Assumptions
* The service exposes a REST API
* The GET /accounts endpoint returns all accounts
* The response is a JSON array of account objects

### Acceptance Criteria
```gherkin
Given 3 accounts exist in the database
When I send a GET request to /accounts
Then I receive a list containing all 3 account records
```
