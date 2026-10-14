---
name: anki-card-generator
description: Converts provided text, notes, or documents into comprehensive theoretical and hands-on practice Anki flashcards following strict spaced-repetition and cognitive learning principles with 100% coverage and zero list answers.
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

---

## Coverage, Content Scope & Formatting Constraints

1. **100% Information Coverage**: Systematically analyze the entire source material to ensure zero concepts, definitions, rules, or core facts are skipped.
2. **Hands-On & Execution Practice**: Generate practice cards that prompt active recall of how something is done (e.g., writing/typing specific syntax, executing code snippets, configuration structures, or step-by-step procedural actions).
3. **Strictly No Lists in Answers**: Answers must never contain lists, comma-separated multiple items, or enumerations (e.g., do not ask for a list of four configuration properties in one answer; instead, split them into separate atomic cards or test them individually).

---

## Language & Tone Guidelines
- Write all questions and answers using clear, simple, and accessible language equivalent to a 7th-grade level, avoiding unnecessarily complex academic jargon without explanation.

---

## Execution Workflow

1. **Exhaustive Parse**: Thoroughly parse the content section by section to identify every core fact, rule, principle, and syntax pattern, targeting 100% coverage.
2. **Atomic Breakdown**: Break down concepts into atomic recall prompts, balancing theory with hands-on "how-to-write" syntax prompts. Ensure no card requires a list or multiple items in the answer.
3. **Deduplication**: Eliminate redundancy and merge overlapping cards while ensuring no unique information or syntax rule is lost.
4. **Refinement**: Rewrite in clear, specific, unambiguous language tailored to a 7th-grade reading standard.
5. **Self-Testing**: Verify against source material—Did we capture everything (100% coverage)? Are there any list answers that need splitting? Would each question make sense in isolation?

---

## Output Formatting Rules
- Output as a list of cards in this exact format:
  ```
  Q: [Question]
  A: [Answer]
  ```
- No numbering unless the user requests it.
- Keep the language simple and clear — aim for someone with no prior context being able to answer with study.
