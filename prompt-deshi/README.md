This project teaches how to build your own skill with a token-efficient workflow.

## Core Idea

Do not depend on a skill-creator loop for every iteration.  
Create your skill files manually, then use AI only where it adds value.

## Recommended Token-Efficient Workflow

1. Build the structure yourself
- Create your own files and folders first:
  - `SKILL.md`
  - `references/references.md` (knowledge base)
  - `example/examples.md` (structured output patterns)

2. Gather raw knowledge
- Collect unstructured references, notes, and ideas.
- Organize them inside `references/references.md`.

3. Create practical examples
- Add real input/output transformations in `example/examples.md`.
- Keep examples reusable and aligned with your target format.

4. Use another LLM for sentence refinement
- Use ChatGPT, Llama, Qwen, or Gemini to polish wording on your skill, references, and examples.
- Ask it to turn rough ideas into clear instruction sentences.
- Keep this model as a writing helper, not the full skill builder.

5. Finalize directly in IDE
- Do minor and final fixes in Cursor or VS Code.
- Clean structure, remove ambiguity, and ensure consistency.
- This saves tokens compared to repeated skill-creator iterations.

6. Wire files correctly in `SKILL.md`
- Reference:
  - `references/references.md`
  - `example/examples.md`
- Verify paths and section flow are correct.

## Why This Saves Tokens

- Fewer long back-and-forth generation cycles.
- More direct edits in the IDE.
- Better use of your main model budget for skill execution.

## Outcome

You get a cleaner, maintainable skill with less token waste and better clarity.
