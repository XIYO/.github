# Contributing to XIYO projects

Thank you for helping improve a XIYO project.

## Before opening a change

1. Read the target repository's README and agent guidance (`AGENTS.md` or `CLAUDE.md`).
2. Search existing issues and pull requests.
3. Open an issue before a large behavior, architecture, or data-format change.
4. Keep a pull request focused on one problem.

## Development expectations

- Run every check documented by the target repository.
- Add or update tests when behavior changes.
- Update consumer documentation when installation, commands, permissions, data handling, or compatibility changes.
- Preserve backward compatibility unless the change is explicitly documented as breaking.
- Do not add deprecated APIs when a supported replacement exists.

## Privacy and diagnostics

Never commit or paste credentials, tokens, private keys, personal messages, calendar contents, phone numbers, email addresses, local database files, or unredacted diagnostic output.

Use synthetic fixtures. If a log is necessary, remove personal content, stable identifiers, filesystem paths, and authentication material before sharing it.

## Pull requests

Describe the user-visible outcome, how it was verified, and any compatibility or privacy impact. Draft pull requests are welcome for early feedback, but they should clearly state what remains incomplete.
