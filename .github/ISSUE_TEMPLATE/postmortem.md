<!-- 

Template from: Betsy Beyer, Chris Jones, Jennifer Petoff, and Niall Richard Murphy. [“Site Reliability Engineering.”](https://landing.google.com/sre/book/chapters/postmortem.html). 

-->

name: PostMortem
description: Create a postmortem
title: "PostMortem Title"
labels: [kind/postmortem, needs/priority, needs/triage]
assignees:
  - 

body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this postmortem! Please be cautious with the sensitive information/logs while filing the issue.

  - type: input
    id: date
    attributes:
      label: Date of the incident ?
      description: todo
      placeholder: YYYY-MM-DD HH:MM:SS
    validations:
      required: true

  - type: input
    id: authors
    attributes:
      label: Authors
    validations:
      required: true

  - type: input
    id: status
    attributes:
      label: Status
    validations:
      required: true

  - type: textarea
    id: summary
    attributes:
      label: Describe the incident clear and concise description of what the incident is.
    validations:
      required: true

  - type: textarea
    id: impact
    attributes:
      label: Describe the impacts
    validations:
      required: true

  - type: textarea
    id: rootcause
    attributes:
      label: Do you find the root causes ?
    validations:
      required: true

  - type: textarea
    id: trigger
    attributes:
      label: 
    validations:
      required: false

  - type: textarea
    id: resolution
    attributes:
      label: How do you resolve it
    validations:
      required: true

<!-- ### Impact

### Root Causes

### Trigger

### Resolution

### Detection

## Action Items

## Lessons Learned

### What went well

### What went wrong

### Where we got lucky

## Timeline

## Supporting information -->