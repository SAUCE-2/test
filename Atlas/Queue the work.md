---
tags:
  - decision
related:
  - "[[Inline or queued]]"
  - "[[Do it inline]]"
---
# Queue the work

**Decided:** Work that can wait runs as a job, not inside the request.

## Why
Doing it on the request made the caller wait, and tied the work to the request's deadline. [[Do it inline]] is the old call. [[Inline or queued]] is the spike.
