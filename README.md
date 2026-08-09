# Rizwan Saleem

Senior Frontend Engineer at [Horsefly Analytics](https://horseflyanalytics.com), Manchester. I build
production TypeScript and React for a labour-market analytics platform, and I work on the AWS and
AI-agent infrastructure behind it.

Most of what I enjoy is the unglamorous half: parser edge cases, streaming protocols, the failure modes
that only show up under real input.

## Open source

I contribute fixes upstream to packages the JavaScript ecosystem depends on.

**Merged**

- [`postcss/postcss-selector-parser#330`](https://github.com/postcss/postcss-selector-parser/pull/330) —
  fixed a `TypeError` thrown on unclosed `[`, `(` and trailing `|` instead of the parser's own error.
  Shipped in [`7.1.5`](https://www.npmjs.com/package/postcss-selector-parser/v/7.1.5).
- [`corsairdev/corsair#111`](https://github.com/corsairdev/corsair/pull/111) — improved the Telegram
  integration plugin.

**Open**

- [`postcss/postcss-selector-parser#335`](https://github.com/postcss/postcss-selector-parser/pull/335) —
  attribute selectors with no valid attribute name threw a raw `TypeError`, or emitted the literal string
  `undefined` into CSS. Verified against 43,200 generated selectors: zero regressions.
- Fixes pending review in `hast-util-from-parse5`, `eslint-plugin-import`, `stacktrace-parser` and
  `xml-js`.

## Packages

[![llm-guard](https://img.shields.io/npm/dm/llm-guard?label=llm-guard)](https://www.npmjs.com/package/llm-guard)
[![bedrock-ui-stream](https://img.shields.io/npm/dm/bedrock-ui-stream?label=bedrock-ui-stream)](https://www.npmjs.com/package/bedrock-ui-stream)

- **[llm-guard](https://www.npmjs.com/package/llm-guard)** — validating and securing LLM prompts, in
  TypeScript.
- **[bedrock-ui-stream](https://www.npmjs.com/package/bedrock-ui-stream)** — bridges AWS Bedrock Agent
  Runtime event streams to the Vercel AI SDK UI message stream protocol. Handles the parts that bite:
  chunk boundaries splitting multi-byte characters, partial tool-call state, and redaction on the error
  path.

## Background

- MSc Computer Science, Manchester Metropolitan University
- AWS Certified Solutions Architect
- Cyber Runway Launch 2024 — the DSIT-funded national cyber accelerator delivered by Plexal
- Volunteer mentor, Manchester Metropolitan University

## Working with

TypeScript · JavaScript · React · Next.js · Node.js · AWS · PostgreSQL · Docker · Terraform

## Elsewhere

[Website](https://rizwansaleem.co) · [LinkedIn](https://linkedin.com/in/therizwansaleem)
