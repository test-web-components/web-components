---
title: "{{ env.RESOURCE }} for {{ payload.issue.title }}"
labels: "{{ env.RESOURCE }}, {{ payload.issue.label }}"
milestone: "{{ payload.issue.milestone }}"
---

Related to: #{{ payload.issue.number }}