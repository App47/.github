name: Bug report
description: Create a report to help us improve
title: "[Bug] - "
labels: ["bug"]
assignees: []
body:
  - type: textarea
    id: what-happened
    attributes:
      label: Describe the bug
      description: A clear and concise description of what the bug is.
      placeholder: What happened? What did you expect?
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to reproduce
      placeholder: |
        1. Go to '...'
        2. Click on '...'
        3. Scroll to '...'
        4. See error
  - type: textarea
    id: expected
    attributes:
      label: Expected behavior
  - type: textarea
    id: screenshots
    attributes:
      label: Screenshots
      description: If applicable, add screenshots to help explain your problem.
    validations:
      required: false
  - type: input
    id: desktop
    attributes:
      label: Desktop info
      placeholder: "OS, Browser, Version"
  - type: input
    id: mobile
    attributes:
      label: Smartphone info
      placeholder: "Device, OS, Browser, Version"
  - type: textarea
    id: context
    attributes:
      label: Additional context
