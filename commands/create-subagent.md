---
description: Create specialized Claude Code subagents with expert guidance
argument-hint: [agent idea or description]
allowed-tools: [Skill(create-subagents)]
---

<objective>
Delegate subagent creation to the create-subagents skill for: $ARGUMENTS

This routes agent development to specialized skill containing subagent patterns, configuration best practices, and creation workflows.
</objective>

<process>
1. Use Skill tool to invoke create-subagents skill
2. Pass agent idea: $ARGUMENTS
3. Let skill handle subagent creation workflow
</process>

<success_criteria>
- Skill successfully invoked
- Agent idea passed correctly to skill
</success_criteria>
