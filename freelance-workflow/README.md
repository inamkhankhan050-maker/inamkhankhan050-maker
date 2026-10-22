# Freelance client workflow

A lightweight, repeatable workflow for small-business website projects. Copy the templates into a private working repository for each real client, then track work with GitHub Issues and milestones. Keep client names, private contact details, credentials, and customer data out of this public toolkit.

## Start a project

1. Copy `templates/project-requirements.md` and collect the brief.
2. Complete `templates/client-onboarding.md` before development starts.
3. Agree on scope, exclusions, deliverables, assumptions, timing, and approval points with `templates/scope-and-deliverables.md`.
4. Create one GitHub milestone per agreed phase or delivery date. Use the outline in `templates/milestones-and-tasks.md`.
5. Copy the issue forms from `github-issue-templates/` into the client's repository at `.github/ISSUE_TEMPLATE/`.
6. Work through `templates/qa-and-launch.md`, record client feedback with `templates/feedback-and-revisions.md`, and hand over with `templates/handover.md`.
7. Agree any post-launch support separately and use `templates/maintenance.md`.

## Suggested GitHub board

Keep one simple project board per active client. Use columns **Backlog**, **Ready**, **In progress**, **Waiting on client**, **Review**, and **Done**. Label work `feature`, `bug`, `content`, `client-input`, or `launch`. Put dates on milestones only after they are agreed. Create tasks after scope approval; do not treat the template as a client record.

## Privacy and access

- Use a private client repository when it contains client assets or non-public information.
- Never commit passwords, API tokens, private customer data, or client account credentials.
- Ask the client to grant the minimum access needed through the service's normal invitation flow. Do not request passwords over chat.
- Keep deployment secrets in the host's secret manager and document variable names, never values.
- Remove client-specific details before reusing any template in a public repository.

## Files

- [Project requirements questionnaire](templates/project-requirements.md)
- [Client onboarding checklist](templates/client-onboarding.md)
- [Scope and deliverables](templates/scope-and-deliverables.md)
- [Milestones and tasks](templates/milestones-and-tasks.md)
- [QA and launch checklist](templates/qa-and-launch.md)
- [Feedback and revisions](templates/feedback-and-revisions.md)
- [Handover checklist](templates/handover.md)
- [Maintenance and support](templates/maintenance.md)
- [Reusable project README](templates/project-readme-template.md)
- [GitHub bug and feature issue forms](github-issue-templates/)
