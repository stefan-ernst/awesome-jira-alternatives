# Awesome Jira Alternatives [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated list of open-source and self-hosted alternatives to [Atlassian Jira](https://www.atlassian.com/software/jira).

This list focuses on tools that you can run on your own infrastructure (or hosted instances of open-source projects). Proprietary closed-source SaaS, abandoned projects, and tools without an English-language documentation are excluded.

## Inclusion criteria

A tool qualifies for this list when it meets **all** of the following:

1. Either uses an [OSI-approved license](https://opensource.org/licenses) **or** is fully self-hostable (a working binary/container that runs without a paid license key).
2. Active development within the last 12 months (commits and a tagged release).
3. First public release at least 4 months ago — keeps the list stable for production users.
4. Documentation available in English.

## Maintainer disclosure

Maintained by [Stefan Ernst](https://github.com/stefan-ernst), who builds [Windshift](https://windshift.sh) — listed below alongside other alternatives. PRs adding direct competitors to Windshift are welcome and will be reviewed on the same criteria as any other entry.

## Contents

- [Full Jira Replacements (self-hosted)](#full-jira-replacements-self-hosted)
- [Kanban-only / Lightweight](#kanban-only--lightweight)
- [Service Desk / ITSM](#service-desk--itsm)
- [Roadmap & Portfolio](#roadmap--portfolio)
- [Hosted Open-Source Alternatives](#hosted-open-source-alternatives)
- [Related Lists](#related-lists)
- [Contributing](#contributing)
- [License](#license)

## Full Jira Replacements (self-hosted)

Tools that aim to cover the full Jira Software / Jira Work Management feature surface — issues, sprints, boards, backlogs, roadmaps.

- [Leantime](https://leantime.io) — Goals-focused PM with strategy, projects, and explicit support for neurodivergent workflows (ADHD, autism, dyslexia). `AGPL-3.0` `PHP` · [Source](https://github.com/Leantime/leantime)
- [OpenProject](https://www.openproject.org) — Comprehensive PM with Gantt charts, agile boards, time tracking, BIM, and meeting management. `GPL-3.0` `Ruby` · [Source](https://github.com/opf/openproject) · [Demo](https://start.openproject.com/)
- [Plane](https://plane.so) — Issues, cycles, modules, and roadmaps with a modern interface and a strong API. `AGPL-3.0` `TypeScript` · [Source](https://github.com/makeplane/plane) · [Demo](https://app.plane.so/)
- [Redmine](https://www.redmine.org) — Veteran PM tool with issues, wiki, time tracking, and a deep plugin ecosystem. `GPL-2.0` `Ruby` · [Source](https://github.com/redmine/redmine)
- [Taiga](https://www.taiga.io) — Agile PM with Scrum and Kanban boards designed for cross-functional teams. `MPL-2.0` `Python` · [Source](https://github.com/taigaio/taiga-back)
- [Tuleap](https://www.tuleap.org) — End-to-end ALM covering requirements, sprints, code, and releases. Used in aerospace and defense. `GPL-2.0` `PHP` · [Source](https://tuleap.net/plugins/git/tuleap/tuleap)
- [Windshift](https://windshift.sh) — Self-hosted work management with boards, backlogs, sprints, and roadmaps. Single Go binary, no external dependencies. `AGPL-3.0` `Go` · [Source](https://github.com/Windshiftapp/core)
- [ZenTao](https://www.zentao.pm) — Scrum-based PM with story, test, build, and release management. Popular in Asian markets. `Z-PL` `PHP` · [Source](https://github.com/easysoft/zentaopms)

## Kanban-only / Lightweight

Trello-style boards and minimalist task tools — for teams that want a board, not a platform.

- [Focalboard](https://www.focalboard.com) — Trello-style board originally MIT, now Mattermost source-available; the standalone build remains usable. `MSAL` `TypeScript` · [Source](https://github.com/mattermost/focalboard)
- [Kanboard](https://kanboard.org) — Minimalist Kanban focused on simplicity and speed. `MIT` `PHP` · [Source](https://github.com/kanboard/kanboard) · [Demo](https://kanboard.org/demo)
- [Planka](https://planka.app) — Trello-like Kanban with real-time collaboration. `Fair-code` `JavaScript` · [Source](https://github.com/plankanban/planka)
- [Tasks.md](https://github.com/BaldissaraMatheus/Tasks.md) — Markdown-file-based Kanban that plays well with file-sync workflows. `MIT` `JavaScript`
- [Vikunja](https://vikunja.io) — To-do app with lists, Kanban boards, Gantt, and a clean API. `AGPL-3.0` `Go` · [Source](https://github.com/go-vikunja/vikunja) · [Demo](https://try.vikunja.io/)
- [Wekan](https://wekan.fi) — Mature open-source Trello clone built on Meteor. `MIT` `JavaScript` · [Source](https://github.com/wekan/wekan)

## Service Desk / ITSM

Alternatives to Jira Service Management — ticketing, helpdesk, and IT service management.

- [FreeScout](https://freescout.net) — Free, Help Scout-style shared inbox for support teams. `AGPL-3.0` `PHP` · [Source](https://github.com/freescout-help-desk/freescout)
- [GLPI](https://glpi-project.org) — IT asset management combined with service desk and helpdesk modules. `GPL-3.0` `PHP` · [Source](https://github.com/glpi-project/glpi)
- [iTop](https://www.combodo.com/itop) — ITSM/CMDB platform with ITIL-aligned workflows. `AGPL-3.0` `PHP` · [Source](https://github.com/Combodo/iTop)
- [osTicket](https://osticket.com) — Long-running ticketing system widely used in education and small business. `GPL-2.0` `PHP` · [Source](https://github.com/osTicket/osTicket)
- [UVdesk](https://www.uvdesk.com) — Symfony-based help desk with mailbox, workflow, and knowledge base modules. `OSL-3.0` `PHP` · [Source](https://github.com/uvdesk/community-skeleton)
- [Zammad](https://zammad.org) — Modern web-based ticketing with email, chat, Twitter, Telegram, and SMS channels. `AGPL-3.0` `Ruby` · [Source](https://github.com/zammad/zammad)

## Roadmap & Portfolio

Alternatives to Jira's Advanced Roadmaps. Most full-platform tools above include roadmapping; standalone roadmap-only options are limited in the open-source space.

- [Leantime](https://leantime.io) — Strategy and goals layer (OKRs) on top of project execution. `AGPL-3.0` `PHP` · [Source](https://github.com/Leantime/leantime)
- [OpenProject](https://www.openproject.org) — Strong Gantt/timeline view across multi-project portfolios. (Full entry above.)
- [Plane](https://plane.so) — Cycles, modules, and cross-project roadmaps. (Full entry above.)

## Hosted Open-Source Alternatives

For teams that want open-source software without operating it themselves.

- [Codeberg](https://codeberg.org) — Hosted [Forgejo](https://forgejo.org) (community-driven Gitea fork) with issues, projects, and milestones. Free for non-commercial projects. `GPL-3.0` `Go`
- [Gitea Cloud](https://about.gitea.com/products/cloud/) — Managed Gitea with issues, projects, and milestones. `MIT` `Go`
- [GitLab.com](https://gitlab.com) — Managed GitLab with issues, boards, milestones, and roadmaps. `MIT` (Community Edition) `Ruby`
- [Plane Cloud](https://app.plane.so) — Managed Plane.so with the same feature set as self-hosted. `AGPL-3.0` `TypeScript`
- [Taiga Cloud](https://tree.taiga.io) — Managed Taiga hosted by Kaleidos Ventures. `MPL-2.0` `Python`

## Related Lists

- [r/selfhosted Wiki — Self-Hosted Alternatives](https://wiki.r-selfhosted.com/learn/self-hosted-alternatives-to-popular-services-and-providers/) — Broad self-hosted alternatives reference.
- [awesome-selfhosted](https://github.com/awesome-selfhosted/awesome-selfhosted) — The canonical self-hosted software list.
- [awesome-homelab](https://github.com/miantiao-me/awesome-homelab) — Curated apps for the homelab crowd.
- [bye-bye-server.com](https://bye-bye-server.com) — Directory of alternatives for teams leaving Atlassian Server / Data Center.

## Contributing

Contributions are welcome. Please read [CONTRIBUTING.md](CONTRIBUTING.md) and follow the [Code of Conduct](code-of-conduct.md).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the maintainer has waived all copyright and related or neighboring rights to the curated list itself. The MIT [LICENSE](LICENSE) covers any code in this repository.
