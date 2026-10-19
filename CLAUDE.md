# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project

OSN — Operating System Next. An operating system written entirely by AI.

- GitHub: https://github.com/sshoecraft/osn (public)
- License: Apache 2.0 with the Commons Clause (`LICENSE`) — free to use, modify and redistribute; selling the software itself is not granted.

## Build, test, architecture

Not yet defined. No source tree, toolchain, target architecture, or build system has been chosen. Fill in these sections when the first one lands.

## Routing Table

When working on a specific area, load the corresponding subsystem doc:

| Task / Area | Load This Doc |
|-------------|---------------|
| Cross-cutting / architecture | `.claude/awareness/structural-map.md` |
| Understanding who calls what | `.claude/awareness/structural-map.md` |

Each subsystem gets a row here and a doc at `.claude/awareness/subsystems/<name>.md`, written from `.claude/awareness/templates/subsystem.md.template`.

## [AWARENESS]

This project uses the three-layer awareness system.

- **Last updated**: 2026-10-18
- **Subsystem docs**: 0 of 0 subsystems documented
- **Structural map**: 2026-10-18, 0 tokens (0 source files)
- **Bootstrap version**: 1.0

Docs location: `.claude/awareness/`
Refresh map: `/project:refresh-map`
Full update: `/project:update-awareness`
