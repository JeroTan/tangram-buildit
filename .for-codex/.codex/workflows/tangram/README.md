# Tangram Workflow Source Mirror

This folder contains the Tangram workflow source material for Codex-side reference:

- `commands/` contains source TOML command prompts.
- `skills/` contains source skill definitions.
- `knowledge/` and `docs/` contain reference material.
- `settings.json` preserves the workflow settings snapshot.

Codex does not execute source TOML command files directly. The Codex-ready version of this workflow is generated in `.agents/skills`, with support material mirrored in `.agents/knowledge` and `.agents/docs`.
