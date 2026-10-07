---
tags:
  - spike
related:
  - "[[Queue the work]]"
ticket: "[[JIRA-1234]]"
---
# Inline or queued

**Question:** Can this work run as a job, or only inside the request?

## What you tried
Sent the same work both ways and compared a delayed job with the inline call.

## What you found
Delay looks like a failure. Still worth leaving the request if delay is reported on its own. The call is [[Queue the work]].
