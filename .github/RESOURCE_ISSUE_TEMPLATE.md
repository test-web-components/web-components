---
title: "{{ env.RESOURCE }} for {{ payload.issue.title }}"
labels: "{{ env.RESOURCE }}"
milestone: "{{ payload.issue.milestone }}"
---

Related to: #{{ payload.issue.number }}