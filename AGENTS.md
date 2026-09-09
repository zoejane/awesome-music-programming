# Repository instructions

These instructions apply to Codex, Cursor, Claude Code, and other coding tools. Read `CONTRIBUTING.md`, then only the files relevant to the task.

## Scope and editing

- This is a public, English-language resource list. Entries and categories live in `README.md`; contribution standards live in `CONTRIBUTING.md`.
- Check `git status --short` and the current branch before editing. Preserve existing and unrelated changes.
- Follow the existing `- [Name](URL) - description` format, use concise English descriptions, and omit trailing periods.
- Check for duplicate entries and place additions in the appropriate category. Verify new or changed factual claims against the project's official sources.
- Follow the existing maintenance and documentation standards; do not add unrelated resources or reorganize the whole list for a small update.

## Validation and publishing

- There is no build system or automated test suite. Review changed links, descriptions, category placement, and Markdown formatting; run `git diff --check`.
- Documentation-only instruction changes need local reference and diff checks; they do not require checking every external resource in the list.
- Follow the branch and pull request process in `CONTRIBUTING.md`. Commit, push, or publish within the current task's authorization; an ordinary edit does not itself authorize publication.
- Do not copy private repository rules, personal records, chat logs, credentials, or private machine paths into this public repository.
