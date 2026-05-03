# Codex Workflow Folder

Codex project configuration lives in `.codex/config.toml`, while reusable workflows are loaded as Codex-ready skills from `.agents/skills`.

This repository's Tangram workflow is organized for Codex as:

- `.agents/skills/tangram-*` for converted Tangram commands
- `.agents/skills/explore-*` and `.agents/skills/design-*` for promoted focused skills
- `.agents/skills/tangram-workflow` as a dispatcher and command map
- `.agents/knowledge` and `.agents/docs` as the Codex-ready Tangram reference library
- `.codex/workflows/tangram` as the source workflow archive

Use `$tangram-workflow` for the command map, or invoke a specific skill such as `$tangram-start`, `$tangram-define`, or `$design-ui`.
