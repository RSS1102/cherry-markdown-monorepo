name: 🚀 New feature proposal
description: Propose a new feature
title: '[feature report]'
labels: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for your interest in the project and taking the time to fill out this feature report!
  - type: textarea
    id: feature-description
    attributes:
      label: Clear and concise description of the problem
      description: 'As a developer using cherry-markdown I want [goal / wish] so that [benefit]. 
    validations:
      required: true
  - type: textarea
    id: suggested-solution
    attributes:
      label: Suggested solution
      description: 'I want a xx function that can be used to do xxx things. Its implementation is beneficial for...'
    validations:
      required: true
  - type: textarea
    id: alternative
    attributes:
      label: Alternative
      description: Clear and concise description of any alternative solutions or features you've considered.
  - type: textarea
    id: additional-context
    attributes:
      label: Additional context
      description: Any other context or screenshots about the feature request here.
  - type: checkboxes
    id: checkboxes
    attributes:
      label: Validations
      description: Before submitting the issue, please make sure you do the following
      options:
        - label: Check that there isn't already an issue that request the same feature to avoid creating a duplicate.
          required: true
    - type: checkboxes
    id: help-us
    attributes:
      label: Help us
      description: Do you plan to submit a PR for this issue? 
      options:
        - label:I would like to try submitting a PR for this issue.
