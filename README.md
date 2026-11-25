# Natural Default Skills

Two reusable instruction packages for OpenClaw:

- [Natural Text Default](natural-text-default/SKILL.md): specific, audience-aware writing and revision, with factual-claim and style checks
- [Natural Media Default](natural-media-default/SKILL.md): restrained art direction, image/video continuity, provider routing and review criteria

Each folder contains its own SKILL.md and the referenced material under references/.

## Installation
Review the instructions first. Copy the selected folder into a user-owned OpenClaw skill directory, such as ~/.openclaw/workspace/skills/, or use a directory configured in skills.load.extraDirs. Avoid overwriting an existing skill with the same name without comparing the versions.

The packages are model-facing guidance, not an executable application. Media generation still requires a separately configured provider/tool and its own credentials, permissions and usage budget. Installing these files does not install a model, grant service access or publish content.

## Repository layout
- natural-text-default/references/anti-patterns.md — editing signals
- natural-text-default/references/evaluation.md — evaluation procedure
- natural-media-default/references/images.md — still images
- natural-media-default/references/video.md — temporal continuity
- natural-media-default/references/providers.md — provider-specific guidance
- natural-media-default/references/rejection-rubric.md — review criteria

## Changes and rights
This README documents the existing published packages; their instruction bodies are unchanged. No private account configuration, conversations, internal runtime state or credentials are included.

No repository-wide licence was specified when this README was added. Public visibility alone does not grant a redistribution licence; obtain permission for uses not otherwise permitted.
