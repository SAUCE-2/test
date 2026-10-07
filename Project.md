# Project

Notes for building a piece of software. The code lives in the repo. This vault is where the words, the calls, and the work sit.

## Where things go

No calendar.

- **Atlas** — notes, spikes, decisions, and Jira notes.
- **Efforts** — work. `status` is `active` or `done`.
- **Concepts** — what a word means. [[Request]], [[Job]], [[Run]].

## Templates

- **Note** — something worth writing down. Goes in Atlas.
- **Spike** — a question you tried to answer. `ticket` points at the Jira task. Goes in Atlas.
- **Decision** — a call you made. Current one: [[Queue the work]]. Goes in Atlas.
- **Effort** — a piece of work. Goes in Efforts. [[Queue the slow work]] links an epic. [[Name the failure fields]] has no ticket.
- **Jira** — a note for a ticket that already exists. Goes in Atlas. Name the file `JIRA-1234`, insert the template, and the link is filled in. Same template for an epic, a story, or a task. Put the parent ticket in `related` when you want that link here.
- **Concept** — a word worth defining. Goes in Concepts.

## Sample

[[JIRA-1]] is the epic, [[JIRA-10]] is the story, [[JIRA-1234]] is the task. The spike [[Inline or queued]] points at the task.

[[Atlas.base|Atlas]] lists the notes. [[Efforts.base|Efforts]] lists the work. Open [[Dynamic.base]] in the sidebar to see what links to the note you have open.
