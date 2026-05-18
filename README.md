# AI Evolution Skills

Practical AI skills from **AI进化俱乐部**.

This repository collects reusable skills, templates, and small scripts for turning repeatable AI workflows into shareable capability packs. The first public skill is a bilingual reader maker: it turns English PDFs or long articles into mobile-friendly Chinese-English study editions.

## Skills

| Skill | What it does | Status |
| --- | --- | --- |
| [`bilingual-reader-maker`](skills/bilingual-reader-maker/) | Make polished bilingual HTML/PDF readers from English source materials. | Stable |

## Design Principles

- **Useful first**: every skill should solve a real workflow, not just demonstrate prompts.
- **Readable for humans**: outputs should be suitable for learners, students, and non-technical users.
- **Mobile-first when possible**: GitHub is the source of truth, but beginner-facing outputs should be easy to open on a phone.
- **No private baggage**: public skills should avoid local paths, private credentials, personal databases, and one-off machine assumptions.
- **HTML as an editable source**: for publishing-style workflows, prefer real-text HTML that can be copied, searched, parsed, restyled, and exported to PDF.

## Install A Skill

Copy a skill folder into your Codex or Claude skills directory.

For Codex:

```bash
mkdir -p ~/.codex/skills
cp -R skills/bilingual-reader-maker ~/.codex/skills/
```

For Claude Code:

```bash
mkdir -p ~/.claude/skills
cp -R skills/bilingual-reader-maker ~/.claude/skills/
```

Then start a new chat/session and ask for the skill by name, or describe the workflow naturally.

## Repository Layout

```text
skills/       Reusable skill packages
templates/    HTML/document templates used by skills
tools/        Small helper scripts for validation and packaging
docs/         Notes on writing, publishing, and installing skills
registry.json Machine-readable skill index
```

## License

MIT. See [LICENSE](LICENSE).

