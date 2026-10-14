---
name: anki-card-generator
description: Converts provided text, notes, or documents into comprehensive theoretical and practical Anki flashcards following strict spaced-repetition and cognitive learning principles with 100% coverage, zero list questions or answers, and chain-of-thought card formulation.
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

1. **100% Information Coverage:** Systematically analyze the entire source material to ensure zero concepts, definitions, rules, or core facts are skipped.
2. **Hands-On & Practical Application:** In addition to theoretical concepts, generate practice cards that prompt active recall of how something is done or applied (e.g., syntax, formulas, execution procedures, step-by-step problem-solving, or applying frameworks to scenarios).
3. **Strictly No Lists in Questions or Answers:** Neither questions nor answers may ask for or contain lists, comma-separated multiple items, or enumerations (e.g., never ask "What are the four core principles...?"; instead, test each principle or item individually using separate atomic cards).

---

## Language & Tone Guidelines
- Write all questions and answers using clear, simple, and accessible language equivalent to a 6th-grade level, avoiding unnecessarily complex academic jargon without explanation.

---

## Execution Workflow (With Chain-of-Thought)

Before generating the final flashcard list, use chain-of-thought reasoning to work through the following internal steps:

1. **Exhaustive Parse & Analysis:** Think through the source material section by section. Map out every core fact, rule, principle, and procedural pattern to ensure 100% coverage.
2. **Atomic Drafting & Decomposition:** Reason about how to break complex ideas into single-fact, atomic recall prompts. Plan both theoretical cards and hands-on application cards.
3. **Constraint Check:** Review drafted cards to ensure no question or answer contains lists, multiple items, or enumerations. Split any multi-item concepts into individual cards.
4. **Simplification & Refinement:** Evaluate the reading level. Reason through how to simplify the wording to a 6th-grade level while preserving precision and context-independence.
5. **Final Quality Check:** Verify that each question makes sense in isolation, tests only one thing, has a single correct answer, and satisfies all methodological principles.

---

## Output Formatting Rules
- Output as a list of cards in this exact format:
  ```
  Q: [Question]
  A: [Answer]
  ```
- Do not include any numbering unless explicitly requested by the user.
- Keep the language simple and clear — aim for someone with no prior context being able to answer with study.
