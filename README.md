# Studio JZ Field Kit

The Field Notes from [softwarebehavior.com](https://softwarebehavior.com), as skills for your AI.

Every Field Note is a short, sourced piece of design research: a finding, what to do, what not to do and where the evidence stops. Here each note is also a skill: a folder with one `SKILL.md` file that your AI tool reads when a task matches. It then applies the finding, respects its limits and names the study, so you can check it.

By Joost van der Zwan · Studio JZ · CC BY 4.0

## The skills

<!-- skills:start -->
| Skill | Note | Use it for | Version | Status |
|---|---|---|---|---|
| `studio-jz-first-glance` | [JZ-002 First impressions](https://softwarebehavior.com/notes/jz-002) | homepages, landing pages, marketing pages, app start screens, store listings, hero sections and any first screen a new visitor sees | 1.0.0 | released |
| `studio-jz-line-length` | [JZ-003 Line length](https://softwarebehavior.com/notes/jz-003) | articles, documentation, help pages, blog posts, long-form reading, email bodies, terms and any column of body text | 1.0.1 | in-review |
| `studio-jz-looks-or-rules` | [JZ-004 Pretty feels easier](https://softwarebehavior.com/notes/jz-004) | visual design of screens, forms, dashboards, kiosks and interfaces; design reviews of a mockup; choosing between a polished and a plain version | 1.0.0 | released |
| `studio-jz-show-the-work` | [JZ-005 Show the work](https://softwarebehavior.com/notes/jz-005) | loading states, progress indicators, search and results screens, AI that is thinking or generating, background jobs and any wait of more than about a second | 1.0.0 | released |
| `studio-jz-algorithm-miss` | [JZ-006 One mistake](https://softwarebehavior.com/notes/jz-006) | recommendations, forecasts, rankings, AI suggestions and generated drafts, autocomplete, and how a product behaves after its model gets something wrong | 1.0.0 | released |
| `studio-jz-head-start` | [JZ-007 Two free stamps](https://softwarebehavior.com/notes/jz-007) | onboarding flows, setup checklists, progress bars, profile completion, loyalty programs and any multi-step goal a user has to finish | 1.0.0 | in-review |
| `studio-jz-apple-corners` | [JZ-008 Apple corners](https://softwarebehavior.com/notes/jz-008) | buttons, cards, app icons, sheets, avatars and any rounded shape in an interface | 1.0.0 | in-review |
| `studio-jz-design-review` | All notes | Reviewing a screen, flow, prototype or screenshot | 1.0.0 | released |
<!-- skills:end -->

Skills marked *in review* are in this repository to read, but not in the downloads yet: they ship when every figure has been checked in the full paper.

## Install

Download one skill, or the whole kit, from [softwarebehavior.com/field-kit](https://softwarebehavior.com/field-kit), or copy a folder from `skills/` in this repository. Each zip holds one folder per skill. Put the folder where your tool looks for skills:

| Tool | Where |
|---|---|
| Claude | Upload the zip of one skill under Customize → Skills and turn it on. Skills need code execution, under Settings → Capabilities |
| Claude Code | `~/.claude/skills/` for all projects, or `.claude/skills/` in a project |
| Codex | `~/.agents/skills/` for all projects, or `.agents/skills/` in a repository |
| GitHub Copilot | `.github/skills/` in your repository |
| Cursor | `.cursor/skills/` in your project |
| Gemini CLI | `~/.gemini/skills/` for all projects, or `.gemini/skills/` in a project |

These locations are checked against each tool's own documentation at every release. Another tool? Every note is also plain markdown at `softwarebehavior.com/notes/jz-00n.md`: paste it into your chat.

Prefer a live connection? Add the Field Kit connector, `https://www.softwarebehavior.com/mcp`, to any AI app that supports MCP connectors. It is read-only and needs no account. Tools: `search_notes`, `get_note`, `review_design`.

## What is in a skill

```
studio-jz-show-the-work/
  SKILL.md            the finding, apply it, do not, limits, example, source and credit
  references/
    evidence.md       every claim, where it is confirmed, and whether it is checked
```

The design review skill (`studio-jz-design-review`) adds `references/index.md` (which note to load for which moment on a screen), one reference file per note, and the frameworks from the book.

## How this repository works

- `skills/` holds one folder per skill. Every file is generated from the Field Note on softwarebehavior.com, so a correction changes the note, not the skill.
- `evals/` holds one test task per skill: run it with and without the skill in two tools before every release.
- A skill is released only when every claim in its evidence list is verified in the full paper.
- `LICENSE` is the CC BY 4.0 license with the credit line. `CHANGELOG.md` lists every release, newest first.

## Corrections

Found a claim that does not match the paper? Open an issue with the page or table number. Corrections ship as a patch release with a changelog line saying what changed and why.

## License and credit

The Field Notes, the skills and the Field Kit are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/): use, share and adapt them, as long as the credit stays:

> Software Behavior Field Notes by Joost van der Zwan · Studio JZ · CC BY 4.0 · softwarebehavior.com

The research belongs to its authors and is cited in full in every skill. The skills summarize the findings; they do not copy the papers' text, figures or tables. The book and the site design keep their own terms.
