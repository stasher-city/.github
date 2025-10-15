---
name: Feature request
about: Suggest an idea for this project
title: "[Feature]"
labels: ''
assignees: ''

---

## Overview
**Description**

Overview of the new feature and how it should help the business (the problem it is solving or the value it adds)

**Proposed solution**

A clear and concise description of what you want to happen.

[ optional

**Describe alternatives you've considered**

A clear and concise description of any alternative solutions or features you've considered.

]

[ optional

**Additional context**

Add any other context or screenshots about the feature request here.

]

**Business value**

How is this feature going to help the business?

- %Value line%
- %Value line%
- %Value line%

## Test Cases:
🔗 Link to Test Cases PR - OR - 🥒 Ghirkin syntax e.g.:

```gherkin
Feature: Search
	Scenario: Search as a logged-out user
		Given I'm a new user
			And Navigated to search page
			And Filled Search Form with location = london and drop off = now and pickup = tomorrow same time
		When  I Click search
		Then  Search Results screen should be visible with 20 results
		
	Scenario: Search as a logged-in user
		Given ...
		When  ...
		Then  ...
```