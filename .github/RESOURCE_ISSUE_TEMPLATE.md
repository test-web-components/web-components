---
title: "{{ env.RESOURCE }} for {{ payload.issue.title }}"
labels: "{{ env.RESOURCE }}, needs-marketing"
milestone: "{{ payload.issue.milestone.id }}"
---

Related to: #{{ payload.issue.number }}