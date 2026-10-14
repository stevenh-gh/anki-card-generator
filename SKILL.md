---
name: anki-card-generator
description: Converts provided text, notes, or documents into high-quality Anki flashcards following strict spaced-repetition and cognitive learning principles.
---

# Anki Card Generator Skill

## Core Methodology & Principles

### SuperMemo’s “20 Rules of Formulating Knowledge”
- Keep questions and answers simple, clear, and concise — one fact per card.
- Break down complex information into atomic facts.
- Use active recall and avoid recognition-only questions unless necessary.
- Avoid cloze deletions unless they make the card simpler and unambiguous.
- Use minimum information principle: include only as much as needed to answer.
- Make cards unambiguous — ensure the question has only one correct answer.
- Use context when needed so the meaning remains clear outside the original text.
- Avoid unnecessary or vague words; use precise, concrete language.
- Avoid “enumerations” — split lists into multiple cards.
- Use visuals only when they meaningfully support recall.

### Andy Matuschak’s Principles
- Frame questions to prompt deep thinking and connection, not just rote recall.
- Where relevant, use “Why…?” or “How…?” questions to promote understanding.
- Avoid trivia in isolation — cards should connect to a bigger mental model.
- Make the answer mentally satisfying to recall — aim for an “aha” moment.
- For abstract concepts, use examples and contrasts.

### Control-Alt-Backspace’s “Precise” Guidance
- Avoid overly broad or fuzzy prompts; make them specific and targeted.
- Ensure questions test only one thing at a time.
- Anticipate common wrong answers and adjust wording to avoid ambiguity.
- Optimize for recall speed — the card should be answerable in 5–10 seconds.
- For concepts that are similar or confusable, differentiate explicitly in the question.

## Language & Tone Guidelines
- Write all questions and answers using clear, simple, and accessible language equivalent to a 7th-grade level, avoiding unnecessarily complex academic jargon without explanation.

## Execution Workflow
1. Parse the content to identify the core facts, relationships, and principles.
2. Break down into atomic, precise recall prompts.
3. Eliminate redundancy and merge overlapping cards.
4. Rewrite in clear, specific, unambiguous language tailored to a 7th-grade reading standard.
5. Test yourself: Would the question still make sense in isolation? Does it have exactly one correct answer?

## Output Formatting Rules
- Output as a list of cards in this format: `Q: [Question]\nA: [Answer]`
- No numbering unless the user requests it.
- Keep the language simple and clear — aim for someone with no prior context being able to answer with study.
