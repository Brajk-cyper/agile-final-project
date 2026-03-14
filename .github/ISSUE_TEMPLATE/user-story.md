---
name: User Story
about: Describe a feature from the perspective of the user
title: 'USER STORY: '
labels: ''
assignees: ''
---

**As a** Catalog Manager
**I need** the ability to create a product in the catalog
**So that** I can add new inventory for customers to purchase.

### Acceptance Criteria

**Scenario: Successfully creating a new product**
* **Given** I am an authenticated Catalog Manager on the inventory page
* **When** I fill out the new product form and click "Submit"
* **Then** the product is saved to the database and appears in the catalog.
