# Prompt Engineering Reference (Anthropic Academy)

## Overview

Effective prompting combines clear communication principles with AI-specific techniques.  

This document defines six foundational prompting techniques and best practices for consistent, high-quality outputs.

---

## 1. Give Context

### Principle

Provide clear background, intent, and purpose.

### Why it matters

AI performs better when it understands:

- What you want

- Why you want it

- Relevant situational context

### Template

- Task:

- Purpose:

- Background:

- Audience (optional):

### Example

Task: Write a LinkedIn post about AI agents  

Purpose: Educate professionals and build authority  

Background: Focus on business productivity gains  

Audience: Mid-level managers  

---

## 2. Show Examples

### Principle

Demonstrate the desired output style or structure.

### Why it matters

Examples reduce ambiguity and align outputs with expectations.

### Template

Input → Output examples:

- Example 1:

- Example 2:

### Notes

- Use 1–3 high-quality examples

- Match format, tone, and structure

---

## 3. Specify Constraints

### Principle

Define boundaries clearly.

### Types of Constraints

- Format (bullet points, JSON, markdown)

- Length (word count, sections)

- Style (formal, casual, persuasive)

- Scope (what to include/exclude)

### Example

- Max 150 words  

- Use bullet points  

- No jargon  

- Focus only on benefits  

---

## 4. Break Complex Tasks into Steps

### Principle

Decompose multi-step problems into structured instructions.

### Why it matters

Improves reasoning, reduces hallucination, increases clarity.

### Template

1. Analyze the problem  

2. Extract key variables  

3. Generate solution  

4. Validate output  

### Example Use Cases

- Strategy planning  

- Workflow design  

- Data analysis  

---

## 5. Ask the AI to Think First

### Principle

Encourage reasoning before answering.

### Why it matters

Improves accuracy and depth.

### Techniques

- “Think step-by-step before answering”

- “Explain your reasoning first”

- “List assumptions before conclusion”

### Note

Use especially for:

- Complex decisions  

- Analytical tasks  

- Problem solving  

---

## 6. Define Role or Tone

### Principle

Assign a role, persona, or communication style.

### Why it matters

Shapes output quality, perspective, and voice.

### Examples

- “Act as a senior product manager”

- “Respond as a data analyst”

- “Write in a persuasive tone”

### Tone Options

- Professional  

- Casual  

- Technical  

- Strategic  

- Educational  

---

## The Secret Weapon: Meta Prompting

### Principle

Use AI to improve your prompt itself.

### Techniques

- “Improve this prompt for clarity and effectiveness”

- “Optimize this prompt for better output quality”

- “Rewrite this prompt using best practices”

### Use Case

- Prompt refinement loop  

- Agent self-improvement  

- Workflow optimization  

---

## Iterative Prompting

### Principle

Prompting is not one-shot — it is iterative and collaborative.

### Process

1. Draft prompt  

2. Evaluate output  

3. Refine prompt  

4. Repeat  

---

## Common Successful Patterns

- Clear task overview

- Explicit format specification

- Defined constraints

- Relevant background context

- Examples when needed

---

## Integration Notes (for Prompt-Deshi Skill)

- Always combine at least 3 techniques per prompt

- Default stack:

  - Context + Constraints + Role

- For complex tasks:

  - Add Step Breakdown + Think First

- For high precision:

  - Add Examples

---

## Quick Prompt Template (Recommended)

Role:  

Task:  

Context:  

Constraints:  

Steps (if needed):  

Examples (if needed):  

---

## Source

Anthropic Academy – AI Fluency: Framework & Foundations