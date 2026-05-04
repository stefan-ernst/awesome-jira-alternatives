# Contributing

Thanks for considering a contribution! This list aims to be a high-signal resource for teams looking to leave Jira.

## Submitting a new tool

1. Open one pull request per tool. Bundled PRs will be asked to split.
2. Confirm the tool meets every [inclusion criterion](README.md#inclusion-criteria) in the README.
3. Add the entry alphabetically within the appropriate section.
4. Use the entry format below exactly.
5. If you maintain or work for the project, disclose it in the PR body.

## Entry format

```markdown
- [Name](https://homepage) — One-sentence description that explains what the tool does and one differentiator. `License` `Language` · [Source](https://github.com/...) · [Demo](https://demo.example)
```

Rules:

- **Name** links to the project's homepage, not its source repository.
- **Description** is a single sentence ending with a period. State what it does and one differentiator. Do not lead with "An open-source...", "A free...", or "A self-hosted..." — those are implied by the list itself.
- **License** uses the [SPDX identifier](https://spdx.org/licenses/) where one applies (`MIT`, `AGPL-3.0`, `GPL-2.0`, etc.). Custom or source-available licenses use a short tag (`MSAL`, `Z-PL`, `Fair-code`).
- **Language** is the primary implementation language, capitalized (`Go`, `Ruby`, `TypeScript`, `PHP`).
- **Source** links to the canonical source repository (GitHub, GitLab, Codeberg, self-hosted Tuleap/Forgejo instance — wherever the project actually lives).
- **Demo** is optional. Include it if a public hosted demo exists.

## Choosing a section

- **Full Jira Replacements (self-hosted)** — Tools that cover issues, sprints, boards, backlogs, and roadmaps as a single platform.
- **Kanban-only / Lightweight** — Board-first tools without sprint/backlog/roadmap features.
- **Service Desk / ITSM** — Ticketing, helpdesk, ITSM, or alternatives to Jira Service Management specifically.
- **Roadmap & Portfolio** — Standalone roadmapping tools, or full-platform tools with notably strong roadmap features.
- **Hosted Open-Source Alternatives** — Cloud-hosted, source-available services. Not for proprietary SaaS.

If a tool fits multiple sections, list it once in its primary category and add a `(see also: ...)` cross-reference in the secondary section.

## Removals

PRs removing entries are welcome when a project becomes archived, abandoned (no commits in 12+ months), or rebranded into something off-topic. Please link evidence (the archived repo, the project's announcement) in the PR description.

## Process

- A maintainer will review within 7 days. Inactivity past that — feel free to ping with `@stefan-ernst`.
- Lint your changes locally with `npx awesome-lint README.md` before submitting.
- Squash commits into a single commit per PR; the message should follow `Add Foo to <Section>` or `Remove Bar (reason)`.
