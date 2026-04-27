# Tangram Buildit

An AI-powered, deterministic CLI workflow for end-to-end software preconstruction, setup, and execution. 

Tangram Buildit is a highly structured, custom AI development workflow designed to tackle the common hurdles of AI-assisted programming. It enforces strict project rules, validates requirements *before* planning, and utilizes Test-Driven Development (TDD) to ensure code quality and predictability.

## Why Tangram Buildit?

Most AI coding tools jump straight into writing code, leading to buggy, inconsistent, and hard-to-maintain projects. Tangram Buildit solves this by enforcing a rigorous **3-Phase Playbook**:

1.  **Preconstruct (The Architect):** Establish your core vision, lock in non-negotiable coding laws (Project Constitution), deep dive into feasibility, and generate project folders with dynamic safety checks.
2.  **Construction (The Builder):** Validate your requirements using an "Agenda" (A brainstorming kit for your feature) before drafting an atomic technical roadmap. Then, execute the plan using strict TDD loops—forcing the AI to write tests before it is allowed to write implementation code.
3.  **Maintain (The Manager):** Keep your project aligned, version-controlled, and safe with dedicated maintenance commands.

## Key Features

-   **Dynamic State Checking:** Proactive safety nets that verify your environment (Node, Python, Git) and project pillars before executing commands, preventing errors before they happen.
-   **Project Constitution:** A living document of your non-negotiable coding laws (e.g., "Strict Vanilla CSS", "No utility classes") that the AI is forced to obey during execution.
-   **Requirements Validation (Agenda):** Interrogates your feature ideas to expose edge cases and ambiguities *before* technical planning begins.
-   **Strict TDD Execution:** The AI must write and fail a test before it writes the code to fix it, drastically reducing the need for manual debugging.
-   **Extension Hooks (`extensions.yml`):** A lightweight plugin system to run custom terminal scripts before or after any Tangram command without modifying the core AI prompts.

## Current Support & Installation

⚠️ **Currently, Tangram Buildit supports the [Gemini CLI](https://github.com/google/gemini-cli) and [OpenCode](https://github.com/google/opencode).**

All workflow commands are built as custom `.gemini/commands/**/*.toml` files.

*Note: There is currently no global initialization script (like `npx tangram-buildit init`). You must manually place the `.gemini` folder into your project root to activate the workflow. Global init scripts may be added in the future!*

## The 3-Phase Playbook

### Phase I: Preconstruct
- `/tangram:define` - Establish your core vision.
- `/tangram:constitution` - Establish non-negotiable project rules.
- `/tangram:explore-*` - Deep dive into feasibility, legacy, and requirements.
- `/tangram:design` - Lock in your 6 technical pillars.
- `/tangram:setup` - Generate project folders and configs.

### Phase II: Construction
- `/tangram:agenda` - Validate requirements before planning.
- `/tangram:plan` - Break down features into atomic tasks.
- `/tangram:execute` - Write tests and code via strict TDD loops.
- `/tangram:debug` & `:complete` - Fix issues and archive work.

### Phase III: Maintain
- `/tangram:commit`, `:align`, `:conditioning`, `:revert` - Version control and safety.