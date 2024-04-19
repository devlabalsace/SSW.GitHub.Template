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
<!-- These comments automatically delete -->
<!-- **Tip:** Delete parts that are not relevant -->
<!-- Next to Cc:, @ mention users who should be in the loop -->
Cc:
<!-- add intended user next to **Hi** -->
Hi {{ USER }}

### Describe the Bug
<!-- A clear and concise description of what the bug is. -->

### To Reproduce
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

### Expected Behavior
<!-- A clear and concise description of what you expected to happen. -->

### Tasks
- [ ] Investigate
- [ ] Fix

### More Information
<!-- Add any other context about the problem here. -->

### Environment
 - Device: [e.g. iPhone 12]
 - Browser: [e.g. chrome, safari]
 - OS: [e.g. iOS]

### Screenshots
<!-- If applicable, add screenshots to help explain your problem. -->


Thanks!
