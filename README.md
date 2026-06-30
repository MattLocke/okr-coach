# OKR Coach Universal Package

This package makes the OKR Coach usable across several AI assistants.

## What to Use

- `agent-skill/okr-coach/SKILL.md`: Agent Skills format for Claude Code and compatible skill loaders.
- `codex/okr-coach/`: Codex skill folder, including `agents/openai.yaml` UI metadata.
- `claude/CLAUDE.md`: Root memory/instructions file for Claude Code projects that do not use skills.
- `github-copilot/.github/copilot-instructions.md`: Repository-wide Copilot instructions.
- `github-copilot/.github/instructions/okr-coach.instructions.md`: Path-specific Copilot instructions for Markdown OKR docs.
- `github-copilot/.github/prompts/okr-coach.prompt.md`: Invokable Copilot prompt file, typically `/okr-coach` in VS Code.
- `github-copilot/.github/agents/okr-coach.agent.md`: Copilot custom agent profile.
- `github-copilot/.github/skills/okr-coach/SKILL.md`: Copilot Agent Skill format.
- `github-copilot/AGENTS.md`: Agent instructions recognized by Copilot cloud agent and other agents that read `AGENTS.md`.
- `generic/okr-coach-system-prompt.md`: Paste-anywhere prompt for assistants without a skill or instruction-file system.
- `a2ui/`: Optional A2UI v0.9 adapter with a sample OKR coaching surface and prompt add-on.

## Notes

- The canonical skill content is `agent-skill/okr-coach/SKILL.md`.
- The Copilot files are wrappers because Copilot can use `.github/copilot-instructions.md`, `.github/instructions/*.instructions.md`, `.github/prompts/*.prompt.md`, `.github/agents/*.agent.md`, `.github/skills/*/SKILL.md`, and `AGENTS.md` patterns.
- Keep all variants outcome-first: audit the goal before rewriting it, detect pilots/experiments, avoid fake ROI, and produce three quarterly Objective options with measurable Key Results.
- Codex can generate A2UI payloads, but Codex skills do not natively render A2UI surfaces. Use the `a2ui/` files with a host application that has an A2UI renderer.

## License

MIT License. Use it, modify it, share it, and adapt it freely.

## Compatibility References

- Claude Code Skills: https://docs.anthropic.com/en/docs/claude-code/skills
- GitHub Copilot repository instructions: https://docs.github.com/en/copilot/how-tos/configure-custom-instructions/add-repository-instructions
- GitHub Copilot prompt files: https://docs.github.com/en/copilot/tutorials/customization-library/prompt-files/your-first-prompt-file
- GitHub Copilot custom agents: https://docs.github.com/en/copilot/reference/custom-agents-configuration
- GitHub Copilot Agent Skills: https://docs.github.com/en/copilot/how-tos/copilot-cli/customize-copilot/add-skills
- A2UI v0.9 protocol: https://github.com/a2ui-project/a2ui/blob/main/specification/v0_9/docs/a2ui_protocol.md
