# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

This is the `.github` repo for the UmmItOS GitHub organization. It has no code, build, or tests. The only real file is `profile/README.md`, which GitHub shows on https://github.com/UmmItOS.

## Editing the profile README

- Facts about UmmItOS (features, install command, requirements) come from the main repo, UmmItOS/UmmItOS. Check that repo or ask the session working on it; don't guess. Only describe what's merged and released on `main`.
- The install command has to be `bash <(curl -fsSL https://raw.githubusercontent.com/UmmItOS/UmmItOS/main/setup.sh)`. Piping `install.sh` into bash breaks: it loads sibling scripts by relative path and asks Y/N questions on stdin.
- Badges are shields.io with `style=for-the-badge` and the purple `7c3aed` accent. Keep new badges in that style.
- Docs live at https://docs.ummit.dev (repo UmmItOS/www).
- `gh repo list UmmItOS` shows the org's repos when the Repositories table needs checking.

## Commits

Conventional Commits, lowercase, short subject, with an optional scope such as `docs(profile): ...`, `style: ...`, `fix: ...`.
