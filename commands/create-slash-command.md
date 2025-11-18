---
description: Create a new slash command following best practices and patterns
argument-hint: [command description or requirements]
allowed-tools: Skill(create-slash-commands)
---

<objective>
Delegate slash command creation to the create-slash-commands skill for: $ARGUMENTS

This routes command creation to specialized skill containing patterns, best practices, and workflows.
</objective>

<process>
1. Use Skill tool to invoke create-slash-commands skill
2. Pass user's request: $ARGUMENTS
3. Let skill handle command creation workflow
</process>

<success_criteria>
- Skill successfully invoked
- Arguments passed correctly to skill
</success_criteria>
