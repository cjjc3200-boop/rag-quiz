# RAG Quiz — drill the mechanism, not the label

A gamified quiz for drilling the *mechanisms* behind the
[`vitos-rag`](https://github.com/cjjc3200-boop/vitos-rag) project.

Most vocab practice teaches you to *recognise* a term. Interviews test whether
you can *explain the mechanism*. Every question here targets a mechanism.

## Play it

Open `index.html` in any browser — no install, no server, no dependencies.

## Modes

- **Quick Round** — 7 random questions across every topic
- **Category Round** — focus one topic until you master it
- **Daily Challenge** — 10 mixed questions
- **Badges** — unlock streaks, level-ups, and perfect rounds

Progress (XP, level, streak, badges) is saved in your browser.

## Categories

1. Embeddings & Vectors
2. Chunking
3. Retrieval & Scoring
4. Production & Guardrails
5. The Pipeline

## Add your own questions

Edit the `BANK` array at the top of the `<script>` in `index.html`. Each entry:

```js
{ cat: "Category", q: "Question text?",
  choices: ["Correct", "Wrong", "Wrong", "Wrong"],
  answer: 0,            // index of the correct choice
  why: "One line explaining the mechanism." }
```
