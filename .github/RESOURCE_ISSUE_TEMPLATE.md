---
title: "{{ env.RESOURCE }} for {{ payload.issue.title }}"
labels: "{{ env.RESOURCE }}, needs-marketing"
milestone: "{{ payload.issue.milestone.url }}"
---

Related to: #{{ payload.issue.number }}