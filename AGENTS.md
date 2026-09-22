# AGENTS.md

## Project purpose

This repository is a Python fundamentals learning module made up of Jupyter notebooks. It is not a production application, package, or service. The main artifacts are the lesson notebooks in the repository root:

- 03_01_getting_started_python_codespaces.ipynb
- 03_02_data_types_operators_input_output.ipynb
- 03_03_decisions_with_conditionals.ipynb
- 03_04_repetition_with_loops.ipynb
- 03_05_lists_and_functions.ipynb
- 03_06_engineering_calculations_automation.ipynb

## Working conventions

- Treat the notebooks as the source of truth for teaching flow and sequence.
- Keep edits aligned with the lesson topic and the file’s numbering/order.
- Prefer small, clear Python examples over large refactors or unrelated cleanup.
- Preserve educational readability: comments, variable names, and outputs should be understandable to learners.
- Avoid changing notebook names or renumbering lessons unless the task explicitly requires it.
- Do not add application architecture or deployment scaffolding that does not match the course format.

## Validation guidance

There is no automated test suite or project build configuration in this repository.

When validating changes:

- Prefer running the relevant notebook cells in Jupyter or VS Code Notebook execution.
- If a change is a standalone Python snippet, validate it with a quick Python execution check.
- For syntax checking on script-like content, use: `python -m compileall .`

## Agent behavior

- Keep changes minimal and instructional.
- When fixing code in a notebook, preserve the lesson narrative and difficulty level.
- If a task would introduce new tooling, packaging, or project structure, stop and confirm the intent before making that change.
- Prefer enhancing explanations and examples over adding unrelated files.

## Typical tasks

This repo is typically used for:

- correcting example code or typos in notebook cells,
- improving explanations or exercise instructions,
- adding clarifying comments or exercises,
- maintaining a consistent teaching progression across modules.
