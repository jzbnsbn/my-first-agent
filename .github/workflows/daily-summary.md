---
on: daily
permissions:
  contents: read
  issues: read
  pull-requests: read
tools:
  github: pull_requests
safe-outputs:
  create-issue:
---

# Daily PR Summary
Create an issue with the executive summary of the activity in the repo yesterday.
