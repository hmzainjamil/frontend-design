# frontend-design

> A prompt-driven design skill for planning distinctive, responsive frontend interfaces and generating implementation guidance.
> **Status:** Single-file skill definition; no packaged application or test suite in this repository.

[Skill instructions](SKILL.md) · [License](LICENSE.txt)

## What it does

The `frontend-design` skill describes a workflow for translating a product brief into an aesthetic direction, design tokens, layout and interaction decisions, then frontend code. Its guidance covers visual archetypes, typography, color, motion, composition, responsive behavior, accessibility, and implementation review.

The repository contains the skill instructions and this README. It does not include a component library, CLI, React application, design-token package, or automated test suite.

## Use the skill

Read [SKILL.md](SKILL.md) and provide it to an AI coding assistant that supports custom skill instructions. The file has YAML front matter naming the skill and a description, followed by the operating guidance.

This repository does not define a package manager, installer, runtime, or automated activation command. Integration steps depend on the host assistant and its current skill format. No generated UI or compatibility check was run as part of this documentation update.

## Workflow in the instructions

1. Identify the product context and users.
2. Choose an aesthetic archetype and one distinct visual anchor.
3. Define typography, color, spacing, and elevation rules.
4. Plan page structure and interaction.
5. Implement and review the result.

The skill is guidance for a coding assistant. It does not itself execute code, enforce accessibility, or guarantee production quality.

## Main guidance areas

| Topic | Where to look |
|---|---|
| Operating sequence and visual archetypes | [SKILL.md](SKILL.md) |
| Typography, color, motion, and composition | [SKILL.md](SKILL.md) |
| Responsive and interaction guidance | [SKILL.md](SKILL.md) |
| Accessibility and implementation review | [SKILL.md](SKILL.md) |

## Scope and limitations

- Advice may need adapting to the target framework, design system, browser support, and project constraints.
- Statements about accessibility are prompts for review, not a conformance result.
- No example app, components, screenshots, browser tests, or benchmark evidence are included in this repository.
- Skill behavior depends on the host AI assistant and the prompt context.

## Contributing

This repository has no `CONTRIBUTING.md` at the reviewed revision. Propose changes through a pull request and explain the intended behavior or wording change. Check the license and preserve attribution.

## License

The repository includes [LICENSE.txt](LICENSE.txt), an MIT License notice with copyright attributed to Alan (2025). Retain that notice in copies and substantial portions.
