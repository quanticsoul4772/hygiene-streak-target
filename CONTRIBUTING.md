# Contributing to hygiene-streak-target

Thank you for your interest in contributing! This repository is intentionally
minimal — at the moment it contains only a `README.md` and a `LICENSE` file.
There is no dependency manifest, no build step, no test suite, and no
automated CI. That makes contributing simple, but it also means human review
carries the full weight of quality control, so please read this guide before
opening a pull request.

## Table of contents

1. [Fork and clone the repository](#1-fork-and-clone-the-repository)
2. [Create a branch for your changes](#2-create-a-branch-for-your-changes)
3. [Keep the README accurate](#3-keep-the-readme-accurate)
4. [Commit message conventions](#4-commit-message-conventions)
5. [Open a pull request](#5-open-a-pull-request)
6. [License](#6-license)
7. [Questions and issues](#7-questions-and-issues)

## 1. Fork and clone the repository

1. Fork the repository on GitHub: open
   [`quanticsoul4772/hygiene-streak-target`](https://github.com/quanticsoul4772/hygiene-streak-target)
   and click **Fork** to create a copy under your own account.
2. Clone your fork to your machine:

   ```bash
   git clone https://github.com/<your-username>/hygiene-streak-target.git
   cd hygiene-streak-target
   ```

3. (Recommended) Add the original repository as the `upstream` remote so you
   can keep your fork in sync:

   ```bash
   git remote add upstream https://github.com/quanticsoul4772/hygiene-streak-target.git
   git fetch upstream
   ```

There is nothing to install or build — the repository is documentation only.
A text editor and `git` are all you need.

## 2. Create a branch for your changes

Never commit directly to `main` in your fork; work on a topic branch instead:

```bash
git checkout main
git pull upstream main   # make sure you start from the latest upstream state
git checkout -b <short-descriptive-branch-name>
```

Use a short, descriptive branch name, for example `docs/clarify-readme` or
`fix/license-typo`. Keep each branch focused on one logical change — small,
single-purpose branches are much easier to review.

## 3. Keep the README accurate

`README.md` is the front door of this project. **Whenever your change alters
the repository's behavior or structure, update `README.md` in the same pull
request** so it stays accurate. Examples:

- You add a new file or directory → mention it in the README if it affects
  how people use or navigate the repository.
- You change what the project does or how it is meant to be used → update the
  README's description to match.

Pull requests that make the README stale will be asked to include the
corresponding README update before they are merged.

## 4. Commit message conventions

Write clear, conventional Git commit messages:

- Use a short summary line of **50 characters or fewer**, written in the
  **imperative mood** ("Add contributing guide", not "Added" or "Adds").
- Capitalize the summary line and do not end it with a period.
- If the change needs explanation, add a blank line after the summary and
  then a body wrapped at ~72 characters explaining **what** changed and
  **why** (the diff already shows *how*).
- Optionally prefix the summary with the area touched, e.g. `docs:`,
  `readme:`, or `license:`.

Example:

```
docs: clarify branch naming in contributing guide

The previous wording did not explain why single-purpose branches are
preferred. Spell out that small branches are easier to review.
```

## 5. Open a pull request

1. Push your branch to your fork:

   ```bash
   git push origin <your-branch-name>
   ```

2. On GitHub, open a pull request from your branch against the `main` branch
   of `quanticsoul4772/hygiene-streak-target`.
3. In the pull request description, explain **what** you changed and **why**.
   Link any related discussion if there is one.

### What reviewers look for

This repository has **no automated CI**, so there are no checks that run on
your pull request — a human reviewer verifies everything. Before you submit,
please self-check the things a reviewer will look at:

- **Correctness of content** — statements in the documentation are accurate
  and reflect the actual state of the repository.
- **README accuracy** — if the change affects behavior or structure, the
  README was updated to match (see section 3).
- **Scope** — the pull request does one thing, and the diff contains only
  changes related to its stated purpose.
- **Writing quality** — clear wording, correct spelling and grammar, and
  Markdown that renders properly (use GitHub's **Preview** tab to check).
- **Commit hygiene** — commit messages follow the conventions in section 4.
- **No phantom references** — the change does not reference commands, tools,
  dependencies, tests, or CI checks that do not exist in this repository.

Reviewers may ask questions or request changes via PR comments; please
respond and push follow-up commits to the same branch.

## 6. License

This project is licensed under the **MIT License** — see the
[`LICENSE`](LICENSE) file at the repository root for the full terms. By
contributing, you agree that your contributions will be licensed under the
same MIT License.

If you want to propose different or additional license terms, do not edit
`LICENSE` unilaterally: open a pull request that modifies the `LICENSE` file
and clearly explain your reasoning in the pull request description, so the
maintainer can discuss and decide.

## 7. Questions and issues

There are no issue templates in this repository yet, so plain free-form
issues are welcome:

- **To ask a question or report a problem**, open an issue on the
  [GitHub issue tracker](https://github.com/quanticsoul4772/hygiene-streak-target/issues).
  Since there is no template to guide you, please include:
  - a clear, descriptive title;
  - what you expected versus what you observed (for problems); and
  - links to any relevant files or lines in the repository.
- **To propose issue templates themselves**, open an issue describing the
  templates you have in mind, or submit them in a pull request for
  discussion.

Thanks again for contributing!
