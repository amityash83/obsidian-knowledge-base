---
title: AI Obsidian Bootstrap Prompt
tags: [system, obsidian, rag, mcp]
domain: ai
difficulty: intermediate
created: 2026-04-09
updated: 2026-04-09
---

# AI Obsidian Bootstrap Prompt

## Summary
This note captures the vault bootstrap requirements used to design the current Obsidian structure. It is preserved as a system reference so future restructuring can follow the same intent.

## Concepts
- System prompts can serve as architectural requirements documents.
- Preserving the bootstrap brief prevents future drift away from the intended note model.
- Requirements notes help both human maintainers and automation agents understand why the vault exists in its current form.

## Commands / Code
```bash
# Review the system bootstrap note
sed -n '1,220p' /Users/amitmishra/temp/ObsidianVault/99-System/ai-obsidian-bootstrap-prompt.md
```

## Architecture / Flow
1. Read the vault requirements.
2. Compare them against the current folder and note design.
3. Use gaps to drive future vault improvements.

## Use Cases
- Re-running vault normalization work later.
- Auditing whether the structure remains RAG-friendly.
- Explaining the original design intent to collaborators or agents.

## Related Topics
- [[dashboard]]
- [[ops-vault-bootstrap-log]]
- [[ai-rag-system-blueprint]]

## Tags
#system #obsidian #rag #mcp

## Source Prompt
# Obsidian Knowledge Base Bootstrap Prompt (RAG + MCP Ready)

## Objective
Analyze and restructure an Obsidian vault into a well-organized knowledge system that is optimized for fast human understanding, future RAG workflows, MCP usage, and long-term extensibility.

## Required Outcomes
- Standardize the folder structure around inbox, projects, knowledge, snippets, logs, and resources.
- Rename notes consistently and enrich every markdown file with metadata and explicit sections.
- Create project and knowledge indexes plus a central dashboard.
- Extract reusable snippets and improve interlinking for search and retrieval.

## Design Constraints
- Do not delete useful information.
- Prefer clarity over brevity.
- Maintain DevOps and AI context.
