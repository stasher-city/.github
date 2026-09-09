# Contributing

These defaults apply to every `stasher-city` repository that does not have its
own `CONTRIBUTING.md`.

## Writing issues, resolutions and PR descriptions

Write for the person who has thirty seconds. Everything else is still welcome,
just folded.

**Above the fold** (the part a reader sees without scrolling or clicking):

- One short paragraph: what, and why it matters. Plain English. No file paths
  unless the reader has to go there.
- Then at most four bullets under one of:
  - `**Done when**` for a task (acceptance criteria, each checkable),
  - `**Decide**` or `**Find out**` for a decision or research question.
- One line `**Recommendation:**` if there is one.
- At most 120 words in total.

**Resolving a question** (a comment that closes a decision or research issue):

- `**TL;DR**`: at most three sentences.
- `**Decision**`: at most four bullets.
- `**Affects**`: links to the issues this changes.

**Everything else** goes in one collapsed block at the end, so nothing is lost
and nobody has to read past it:

```markdown
<details><summary>Detail</summary>

Evidence, file and line references, option analyses, env-var lists, policy
JSON, citations.

</details>
```

Fold, do not delete. A decision-relevant fact that is not in the issue somewhere
is a defect; a fact that is above the fold when it did not need to be is a
smaller one.

**Why:** the ask is the part people act on, and a wall of evidence in front of it
means they stop reading before they reach it. The first draft of a large
migration map averaged 160 words of flat prose per issue and one research
resolution ran to 900 words before its three-sentence conclusion. Folding the
detail took the visible part to about 100 words per issue with nothing removed.
