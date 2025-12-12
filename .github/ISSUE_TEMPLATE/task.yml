name: Task
description: Track a unit of work with acceptance criteria
title: "[Task] - "
labels: ["task"]
assignees: []
body:
  - type: textarea
    id: summary
    attributes:
      label: Summary
      description: Briefly describe the task and outcome.
      placeholder: "Implement X, refactor Y, write docs for Z..."
    validations:
      required: true
  - type: dropdown
    id: area
    attributes:
      label: Area
      description: What part of the system does this affect?
      options:
        - backend
        - frontend
        - mobile
        - infra
        - docs
        - qa
        - design
  - type: dropdown
    id: priority
    attributes:
      label: Priority
      options: ["low", "medium", "high", "critical"]
    validations:
      required: true
  - type: input
    id: estimate
    attributes:
      label: Estimated effort
      placeholder: "e.g., 2h, 1d, 3d"
  - type: textarea
    id: steps
    attributes:
      label: Implementation notes / checklist
      description: Break the work into actionable steps.
      placeholder: |
        - [ ] Step 1
        - [ ] Step 2
        - [ ] Step 3
  - type: textarea
    id: acceptance
    attributes:
      label: Acceptance criteria
      description: Define pass/fail checks for this task.
      placeholder: |
        - [ ] Criteria 1
        - [ ] Criteria 2
        - [ ] Criteria 3
    validations:
      required: true
  - type: input
    id: due
    attributes:
      label: Target date (optional)
      placeholder: "YYYY-MM-DD"
  - type: textarea
    id: context
    attributes:
      label: Additional context
      description: Links, screenshots, related issues/PRs.
