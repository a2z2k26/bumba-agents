# Bumba Agents

Collection of 40 specialist agents organized by department prefix (design-*, engineering-*, qa-*, ops-*, strategy-*). Each agent has a system prompt defining its role, tools, and expertise.

## Architecture
- 5 department chiefs coordinate within departments
- Agents are defined in `~/.claude/agents/`
- This repo contains agent definitions, templates, and orchestration patterns

## When Working Here
- This is a reference/configuration repo — changes affect agent behavior across all projects
- Test agent changes in isolation before committing
- Maintain consistency in system prompt structure across agents
