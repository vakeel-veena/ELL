# LLM Playbook – Leadership Development Program

## Purpose
Ensure consistency, traceability, and quality when using multiple LLMs
to support a leadership development program.

## Core Principle
One source of truth. All LLMs consume the same context.

---

## LLM Roles
- LLM-A: Program Designer
- LLM-B: Communication Lead
- LLM-C: Critical Reviewer

Each LLM has a distinct role. No overlap.

---

## Standard System Prompt (Mandatory)
You are supporting a leadership development program for senior ICs.
Use the provided Master Context as the single source of truth.
Do not invent program details.
Flag assumptions explicitly.
Optimize for clarity, practicality, and executive credibility.

---

## Prompt Structure (Mandatory)

CONTEXT  
Use Leadership Program Master Context vX.X below.

[PASTE CONTEXT]

ROLE  
You are acting as: <Designer / Communicator / Reviewer>

TASK  
<One clear sentence>

CONSTRAINTS  
- Audience:
- Tone:
- Length:
- Format:
- Avoid:

---

## Change Management
Any change requires:
1. Update MASTER_CONTEXT.md
2. Increment version
3. Log change in CHANGELOG.md
4. Use updated context in all LLM prompts

---

## Weekly Rhythm (10–15 mins)
- Review feedback
- Update context if needed
- Log decisions
- Commit changes

No updates = still commit a review note.
