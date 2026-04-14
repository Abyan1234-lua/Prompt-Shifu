# Prompt Deshi (Educational Skill)

This project is for educational purposes: it shows how to create your own Agent skill from scratch, refine it with AI, and connect supporting documents in a clean, reusable structure.

## Purpose

`prompt-deshi` demonstrates a practical skill-authoring workflow:
- define what the skill should do,
- gather quality reference material,
- build examples,
- iterate with AI for clarity,
- and finalize a structured `SKILL.md` that reliably uses supporting files.

## Project Structure

- `SKILL.md` - main skill instructions and behavior rules.
- `references/references.md` - foundational prompt engineering concepts and guidance.
- `example/examples.md` - before/after or pattern-based refinement examples.

## Step-by-Step Workflow

1. Define the skill goal
- Write one clear sentence for the skill's objective.
- Decide trigger phrases (for example: "refine this prompt", "optimize this prompt").
- Define expected output format and guardrails.

2. Gather references
- Collect reliable prompting principles and frameworks. (it can be youtube videos, books, and other sources. Basically for RAG)
- Store and organize them in `references/references.md`.
- Keep content practical and reusable, not just theoretical.

3. Build examples
- Add realistic raw prompts and refined outputs in `example/examples.md`.
- Cover multiple cases (simple, medium, complex).
- Keep examples consistent with the skill's intended style.

4. Iterate with AI for clarity
- Ask AI to review wording, ambiguity, and instruction order.
- Tighten vague statements into explicit rules.
- Repeat until sections are short, clear, and actionable.

5. Fine-tune `SKILL.md` with AI
- Ensure `SKILL.md` has proper YAML frontmatter (`name`, `description`).
- Keep the structure standard: triggers, workflow, output rules, template, guardrails.
- Verify mandatory behavior is explicit and easy to follow.

6. Connect files correctly
- Make sure `SKILL.md` points to:
  - `references/references.md`
  - `example/examples.md`
- Use consistent relative paths so the agent can read the right files.

7. Validate and polish
- Remove redundant text and conflicting instructions.
- Check for model-agnostic wording.
- Confirm the final flow produces clear, consistent refined prompts.

## Recommended Iteration Loop

Use this loop each time you improve the skill:
1. Update references or examples.
2. Ask AI to evaluate gaps and ambiguity.
3. Refine `SKILL.md` instructions.
4. Test with sample raw prompts.
5. Repeat until output quality is stable.

## Outcome

By following this process, you learn how to design a robust, maintainable skill that is easy to extend and produces high-clarity outputs consistently.
