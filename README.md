# Git training checks

This is a practice repository for the linting and CI module. It contains made-up files only.

It has three automatic checks that run on every pull request:

| Check | What it does | Looks at |
|---|---|---|
| `lint-markdown` | Checks Markdown style with a tool called markdownlint | the `docs/` folder |
| `lint-yaml` | Checks YAML style with a tool called yamllint | the `config/` folder |
| `pr-title` | Checks that the pull request title follows the Conventional Commits format | the PR title |

## Where to look on GitHub

Open the **Actions** tab to see each run, and open a pull request to see the checks listed near the
bottom of the page. A green tick means the check passed and a red cross means it failed. Click
**Details** to read the messages.

## The exercise files

`exercises/module-5/` holds files with deliberate problems. They are not checked until you copy
one into `docs/` or `config/` on a branch.

## Ground rules

1. Work only in your own copy of this repository.
2. Never put real passwords, keys or business data in any file here.
