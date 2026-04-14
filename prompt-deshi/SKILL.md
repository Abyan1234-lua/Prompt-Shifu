---
name: prompt-deshi
description: Refines raw user prompts into clear, structured, model-agnostic prompts with explicit role, task, and constraints. Use when the user asks to refine, improve, optimize, or rewrite a prompt for better AI results.
---

# Prompt Deshi

Transform raw, human-written prompts into clear, structured prompts that preserve intent and improve output quality.

## Trigger Conditions

Use this skill when the user says phrases like:

- "refine this prompt"
- "improve this prompt"
- "optimize this prompt"
- "rewrite this prompt for AI"

Or uses commands like:

- `/prompt-deshi`

## Initial Response

If triggered before the user provides the raw prompt, reply with exactly:

`Sure-copy paste your prompt, leave the tuning to me.`

Then wait. Do not ask follow-up questions and do not provide multiple options.

## Workflow

1. Read references:
  - `references/references.md`
  - `example/examples.md`
2. Extract the original intent and preserve it.
3. Add missing context and assign the best-fit expert role.
4. Convert vague instructions into explicit constraints (length, tone, style, scope).
5. Structure the prompt for execution quality and logical flow.
6. Add optional sections only when needed (`Steps`, `Think First`, `Structure`, `Output Format`).
7. Ensure model-agnostic wording and direct executability.

## Output Rules

- Output only the refined prompt.
- Do not include explanations, notes, or comments.
- Do not reference source files in the final output.
- Keep the result concise but complete.

## Output Template

Use this structure (omit optional fields if unnecessary):

```text
Role:
Task:
Context:
Constraints:
Structure: (optional)
Steps: (optional)
Think First: (optional)
Output Format: (optional)
```

## Guardrails

- Do not change original user intent.
- Do not introduce unrelated assumptions.
- Always include `Role`, `Task`, and `Constraints`.
- Add `Context` when missing.
- Use measurable, concrete wording instead of vague terms (for example: replace "better" with specific criteria).
- Avoid model-specific syntax; keep language portable across major LLMs.

## License

This skill is licensed under the MIT License. See `LICENSE`.

