---
title: Obsidian Vault README
tags: [readme, knowledge-base, obsidian, rag, mcp]
domain: knowledge-management
difficulty: beginner
created: 2026-04-10
updated: 2026-04-10
---

# Obsidian Vault README

## Purpose
This vault is a personal DevOps and AI knowledge system built for structured note-taking, long-term reuse, and future automation. It is designed to support three outcomes:

- Human-readable technical documentation
- RAG-ready knowledge retrieval
- MCP-style agent workflows for reasoning and execution

## Primary Use Cases
- Capture architecture discussions, debugging sessions, and implementation decisions.
- Store project context and proof-of-concept learnings in a reusable format.
- Keep operational commands and templates in one searchable place.
- Prepare notes for future AI querying and agent-driven task execution.

## Folder Structure

### `00-Inbox/`
Use for raw capture before classification.

Typical content:
- rough notes
- chat summaries
- unprocessed ideas
- temporary discussion dumps

### `01-Projects/`
Use for active project notes and project-level context.

Typical content:
- project overview notes
- implementation plans
- POC summaries
- project indexes

### `02-Knowledge/`
Use for durable domain knowledge that should remain stable beyond a single project.

Typical content:
- Kubernetes concepts
- Terraform workflows
- LLM and RAG notes
- networking references

### `03-Snippets/`
Use for reusable commands, templates, and short execution patterns.

Typical content:
- `kubectl` command sets
- Terraform CLI workflows
- RAG pipeline templates

### `04-Logs/`
Use for historical records and operational timelines.

Typical content:
- vault update logs
- experiment logs
- migration records
- implementation milestones

### `05-Resources/`
Use for canonical references and curated maps of important notes.

Typical content:
- reference maps
- curated entry points
- stable navigation notes

### `99-System/`
Use for system prompts, vault rules, and design constraints that define how the knowledge base should evolve.

Typical content:
- bootstrap prompts
- structure rules
- operating instructions

## How To Use This Vault
1. Start from [dashboard.md](/Users/amitmishra/temp/ObsidianVault/dashboard.md).
2. Capture incomplete information in [00-Inbox/inbox-capture-staging.md](/Users/amitmishra/temp/ObsidianVault/00-Inbox/inbox-capture-staging.md).
3. Move durable technical knowledge into [02-Knowledge/index.md](/Users/amitmishra/temp/ObsidianVault/02-Knowledge/index.md).
4. Keep project-specific work under [01-Projects/index.md](/Users/amitmishra/temp/ObsidianVault/01-Projects/index.md).
5. Extract repeatable commands into `03-Snippets/`.
6. Record important changes in `04-Logs/`.

## Note Design Standard
Each note should be:

- self-contained
- explicit and technical
- easy to scan
- linked to related notes
- tagged for retrieval

Recommended note sections:
- `Summary`
- `Concepts`
- `Commands / Code`
- `Architecture / Flow`
- `Use Cases`
- `Related Topics`
- `Tags`

## Naming Convention
Use descriptive kebab-case file names with domain context when possible.

Examples:
- `kubernetes-cluster-fundamentals.md`
- `terraform-infrastructure-workflows.md`
- `ai-rag-system-blueprint.md`

## Tagging Guidance
Prefer structured and searchable tags.

Examples:
- `#infra/kubernetes`
- `#tool/terraform`
- `#project/mcp`
- `#learning`
- `#rag`

## RAG Readiness Guidelines
To keep notes retrieval-friendly:

- use clear headings
- keep paragraphs short
- avoid vague references
- include concrete technical terms
- preserve metadata in frontmatter
- add related links for context expansion

## MCP Readiness Guidelines
When a note includes repeatable operational work, identify:

- what can be automated
- what can become a runbook
- what tools or APIs are needed
- what inputs and outputs an agent would need

Useful MCP breakdown:
- Knowledge Layer: Obsidian notes and indexed markdown
- Reasoning Layer: LLM plus retrieval
- Execution Layer: CLI tools, scripts, APIs, and validations

## Recommended Workflow
Chat or rough notes -> `00-Inbox/` -> structured project or knowledge note -> snippet extraction -> linked references -> automation candidate

## Key Entry Points
- [dashboard.md](/Users/amitmishra/temp/ObsidianVault/dashboard.md)
- [01-Projects/index.md](/Users/amitmishra/temp/ObsidianVault/01-Projects/index.md)
- [02-Knowledge/index.md](/Users/amitmishra/temp/ObsidianVault/02-Knowledge/index.md)
- [05-Resources/platform-reference-map.md](/Users/amitmishra/temp/ObsidianVault/05-Resources/platform-reference-map.md)
- [99-System/ai-obsidian-bootstrap-prompt.md](/Users/amitmishra/temp/ObsidianVault/99-System/ai-obsidian-bootstrap-prompt.md)
