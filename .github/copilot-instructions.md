# GitHub Copilot Instructions

## Purpose
This file helps the Copilot Chat agent work effectively in this repository by describing the current workspace state and the preferred way to assist.

## Repository status
- Current workspace contains only an image file: `kitlogo (1).png`.
- No source code, build scripts, tests, or documentation files are present.

## How to help
When asked to make changes:
- Verify the repository contents first.
- If the workspace is empty or contains only non-code assets, clearly say so and ask for the source files or a more complete repository snapshot.
- Avoid making assumptions about architecture, language, or build tools unless the user provides them.

## If files are added later
Once source files are available, update this file with:
- repository language and framework
- build and test commands
- common directory layout
- coding and formatting conventions
- any project-specific tooling or CI expectations

## Agent behavior
- Prefer small, safe changes when repository content is limited.
- Document uncertainties explicitly.
- Ask clarifying questions before editing if the user's intent is unclear.
