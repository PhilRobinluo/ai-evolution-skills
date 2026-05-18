# Bilingual Reader Maker

Turn English PDFs or long articles into polished bilingual study readers.

The default reading experience is mobile-friendly:

```text
English paragraph
Chinese translation

English paragraph
Chinese translation
```

This avoids hard-to-read side-by-side columns on phones while keeping the material useful for language learning, quoting, parsing, and annotation.

## What It Produces

- HTML: real text, editable, searchable, parseable
- PDF: exported from HTML for sharing
- Optional source-style cover/chapter pages
- Optional subtle final attribution/colophon

## Install

Copy this folder into your skills directory:

```bash
cp -R skills/bilingual-reader-maker ~/.codex/skills/
```

or:

```bash
cp -R skills/bilingual-reader-maker ~/.claude/skills/
```

## Example Prompt

```text
Please turn this English PDF into a Chinese-English bilingual mobile reading edition.
Keep the original cover style, but make the body single-column for phone reading.
Export both HTML and PDF.
```

