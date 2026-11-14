# Profile repository guide

## Purpose and files

This repository contains Ihsan Mirani Rumi's GitHub profile. The main deliverable
is `README.md`, written for recruiters, engineering peers, and collaborators.
It is a Markdown profile, with no application build or test suite.

- `README.md`: public profile, contact links, experience, skills, and education.
- `welcome-header.gif`: existing optional asset; currently unused. Preserve it
  unless an asset change is requested.
- `AGENTS.md`: reusable instructions for future profile updates. Keep this file
  public-safe too.

## Quick update workflow

1. Read this file, `README.md`, and `git status --short --branch`.
2. Work on a topic branch. Reuse the current branch for the same ongoing task;
   create a descriptive new branch before starting a separate update. The user
   explicitly requested branch-based work. Preserve unrelated local edits.
3. Use the user's latest supplied CV, contribution notes, and corrections to
   update the relevant sections directly. Routine wording and layout choices
   do not need confirmation. Ask only when a material fact cannot be resolved.
4. Prefer focused edits over rewriting the entire profile or adding every item
   from a contribution register. Remove repetition and superseded claims.
5. Review the diff and run `git diff --check`. Manually check Markdown links,
   table structure, heading order, and balanced `<details>` tags. No dependency
   installation, automated tests, or website tooling is needed for prose edits.
6. Report the files changed, branch, validation, and commit/push status. Commit,
   push, or publish only when authorized by the user's request or session.

## Content and presentation

- Lead with platform engineering, Kubernetes/GitOps, and Go/gRPC backend work.
  Use first-person, concrete language and a professional, approachable tone.
- Keep contact links near the top. The contact email supplied for this refresh
  is `hello@imrumi.dev`. Preserve the existing portfolio URL unless the user
  supplies a replacement; do not infer a website URL from the email domain.
- Keep career progression and dates in Experience; keep cross-role engineering
  contributions in Selected engineering work when their exact dates are unknown.
- Use a compact skills table. Distinguish backend feature development from
  deploying or operating applications built by colleagues or upstream projects.
- Keep lab work clearly labelled. Preserve education, courses, research, and
  achievements unless the user updates them; secondary material can remain in
  the collapsible Research & achievements section.
- Describe AWS Academy items as courses, not AWS professional certifications.
- Favor readable Markdown, short paragraphs, and selective bullets. Avoid badge
  walls, external stats widgets, repeated contact sections, and decorative clutter.
- Use `<br>` when a hard line break is needed, rather than trailing spaces.
- Use the current README for existing facts rather than duplicating a full CV
  here. Refresh this guide only when a lasting preference or workflow changes.

## Contribution accuracy

The November 2026 refresh used a user-supplied CV and a sanitized CarryBee
contribution register. The register is not stored in this repository. Do not
claim to have inspected its private source artifacts or require that archive
again for ordinary profile edits.

- User-confirmed implementation, deployment, and troubleshooting support direct
  contribution wording. Lack of an archived runtime result does not erase that
  ownership, but it does limit claims about measured outcomes.
- Preserve shared attribution for cloud migrations and PostgreSQL ARM migration.
  Do not upgrade "contributed" or "supported" to sole leadership or ownership of
  the entire platform without new confirmation.
- Keep development, staging, production, and local R&D distinct. Transport API
  delivery was reported through staging; Alloy/Tempo tracing was lab work.
- Do not equate configuration with a successful rollout, a running process with
  complete health coverage, or service reachability with verified HA/failover.
- Do not invent uptime, throughput, cost savings, recovery times, zero data loss,
  or deployment-speed improvements. Add metrics only when the supplied material
  supports their scope and public use; resolve conflicts rather than combining
  incompatible numbers from older profile versions.
- Do not imply authorship of upstream applications, Helm charts, ML models, or
  colleague-authored scripts when the contribution was integration or operation.
- Publish concise engineering contributions, not private evidence registers,
  internal endpoints, credentials, customer data, or operational incident details.
