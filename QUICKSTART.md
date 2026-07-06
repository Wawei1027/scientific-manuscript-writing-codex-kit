# Quickstart

This guide helps you install and test the Scientific Manuscript Writing Codex Kit.

## 1. Install the plugin marketplace

From a terminal with Codex available, run:

```bash
codex plugin marketplace add Wawei1027/scientific-manuscript-writing-codex-kit --ref manuscript-writing-skills
codex
/plugins
```

If you are testing this documentation branch before merge, use:

```bash
codex plugin marketplace add Wawei1027/scientific-manuscript-writing-codex-kit --ref docs/toolbox-polish-20260706
```

## 2. Confirm the skills are visible

Inside Codex, open `/plugins` and confirm that `scientific-manuscript-writing-kit` is installed. The skills should include manuscript structure editing, microbiome Results writing, Discussion logic, Methods reproducibility auditing, journal style adaptation, cover letters, reviewer responses, and scientific English polishing.

## 3. Run a smoke test

Try one prompt from `examples/smoke-test-prompts.md`, for example:

```text
Use the manuscript-structure-editor skill to review this manuscript outline for logic, novelty, section flow, and claim support: [paste a non-sensitive outline].
```

## 4. Safety expectations

Do not place real unpublished manuscripts, private reviewer comments, raw data, application materials, API keys, or sensitive correspondence in this repository. Use placeholders or sanitized excerpts for testing.
