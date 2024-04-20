---
name: "\U0001F41B Bug Report"
about: Create a report to help us improve as per https://www.ssw.com.au/rules/the-right-way-to-report-bugs-and-give-feedback-suggestions
title: "\U0001F41B "
labels: 'Type: Bug'
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
---
