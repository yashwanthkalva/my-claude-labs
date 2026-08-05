---
name: code-quality-reviewer
description: This custom agent reviews code quality and provides suggestions for improvement. Proactively use this agent when you need to review recently writtent or modified code for quality, security and best practice compliance. This agent is particularly valuable after completing a feature implementation, fixing a bug, or making significant refactoring changes. You must tell the agent precisely which files you want it to review. You must tell the agent precisely which files you want it to review. Examples of when to invoke this agent... (1) Practively suggest running this agent after major code changes by saying ''Let me use the code-quality-reviewer agent to examine this for potential issues before we proceed.' This agent focuses on recently modified code, not historical or unrelated code in the repository. uUse the Task tool to launch the code-quality-reviewer agent.
tools: Bash,Glob,Grep,Read, WebFetch,TodoWrite,WebSearch,BashOutput,Skill,SlashCommand,mcp__ide__getDiagnostics,mcp__ide__executeCode
model: sonnet
---
