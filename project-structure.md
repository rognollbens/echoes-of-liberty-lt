# Project Structure and Workflow

This document outlines the structure and collaborative process for the Echoes of Liberty translation project.

## File Structure

- `/source` – contains the original English texts (or other source languages) in markdown files.
- `/translation` – contains the Lithuanian translations, mirroring the structure of `/source`.
- `/glossary` – a glossary file (`glossary.md`) that defines key terms and their agreed-upon Lithuanian equivalents to maintain consistency across translations.
- `/docs` – additional documentation, style guides, and contributor guidelines (optional).
- `README.md` – project overview and instructions.

## Collaborative Process

1. **Choosing a text**: Contributors should first check the `/source` directory for untranslated texts. If a text is not yet present, it can be added to `/source` in a separate branch.
2. **Translation branch**: Create a new branch from `main` with the naming convention `translate/<text-name>`.
3. **Source file**: Place the original text (in English) in `/source/<text-name>.md`.
4. **Translation file**: Create the corresponding Lithuanian translation in `/translation/<text-name>.md`.
5. **Pull Request**: Open a pull request from the translation branch to `main`. The PR description should include notes on any difficult phrases, stylistic choices, or questions for reviewers.
6. **Review**: At least one other contributor should review the translation before merging. Comments on phrasing, terminology, and style are encouraged.
7. **Glossary updates**: If new key terms are introduced, they should be added to `/glossary/glossary.md` (or discussed in the PR).
8. **Merge**: Once approved, the PR can be merged (preferably with a squash merge to keep history clean).

## Getting Started

- Start by translating the introduction (see the `translate/introduction` branch).
- Refer to this document for any questions about the workflow.
- Feel free to propose improvements by opening an issue or pull request.