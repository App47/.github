name: Bug Report
description: File a bug report.
title: "[Bug]: "
labels: ["bug", "triage"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: textarea
    id: what-was-expected
    attributes:
      label: What did you expect to happen?
      description: Tell us what the expected outcome was.
      placeholder: Tell us what you expected
      value: "I should have been logged into the system"
    validations:
      required: true
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Tell us what really happened
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
  - type: textarea
    attributes:
      label: Operating System
      description: What operating system are you using?
      placeholder: "Example: macOS Big Sur"
      value: operating system
    validations:
    required: true
