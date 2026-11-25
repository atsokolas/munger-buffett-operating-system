# Directions for agents using this repo

This repo is a decision system, not a quote book. Use it to make fewer
preventable mistakes, not to sound more like Munger or Buffett.

## Read order

1. `README.md` — what this is, what it is not, the quotation rule.
2. `executive-brief.md` — the 12 principles and how the philosophy evolved.
3. `operating-framework.md` — the 10-step master sequence and the variants.
4. `cited-reference.md` — the chronological evidence behind the principles.
5. `methodology-and-corpus.md` — source grades, coverage, and limits.
6. `notes/munger-core-framework.md` — the 9-layer error-control architecture.

## Using it on a live decision

Run the 10-step sequence in `operating-framework.md` in order: define the
decision, establish survival constraints, test the circle of competence, build
the model lattice, audit incentives and psychology separately, invert and
pre-mortem, force disconfirmation, compare opportunity costs, decide and size
with conditions, then record and learn.

Record the decision with `decision-record.md` **before** the outcome is known.
Allowed competence outputs are `inside`, `learnable before the deadline`, and
`too hard` — never fill a `too hard` slot with a guess. Preserve what was known
at the time; do not rewrite the original thesis at review.

For a maintained judgment (an investment, a product call, a hire), use the
dossier variant in `decision-record.md`: current claim, confidence and evidence
quality, attached sources, what changed, what strengthened, what weakened, open
questions, decision / next move, review trigger.

## The quotation rule

- Grade A or clean Grade B sources: quotable **after checking the underlying
  text**. The underlying text is not in this repo — fetch it from the source
  listed in `corpus-sources.md` and verify the wording before quoting.
- Grade C (meeting notes, third-party transcripts): paraphrase. Exact wording
  needs independent confirmation.
- Grade D: discovery only. No load-bearing quotation.
- Never invent a Munger or Buffett quotation. Never present this synthesis as
  their verbatim words. Attribute paraphrase as paraphrase.
- File availability does not imply quotation fitness.

## Wiring it into an agent

Point the agent's configuration at this repo's framework files, e.g.:

- Decision procedure: `operating-framework.md` (master sequence + variants)
- Decision record: `decision-record.md`
- Principles: `executive-brief.md`
- Evidence and limits: `cited-reference.md`, `methodology-and-corpus.md`

Suggested standing instruction: "When advising on a consequential decision,
run the 10-step sequence in `operating-framework.md` and record it with
`decision-record.md`. Apply the quotation rule in `README.md` before quoting
Munger or Buffett. If the decision is outside the circle of competence, say
`too hard` and stop."

## What not to do

- Do not treat this as a live corpus. Source cutoff is August 3, 2026; nothing
  after that date is in it, and 7 of the 145 items were never extracted as text.
- Do not claim the corpus is included. It is not, and it must not be added:
  the 145 items are copyrighted primary sources. Link to them; do not
  redistribute them.
- Do not use a single model as decoration. Every model in the lattice must be
  able to change the decision, or leave it out.
- Do not convert every disappointment into "long term." Thesis-breakers are
  set in advance and honored.
- Do not maximize output count. The point of the system is fewer, better
  decisions — not more notifications, documents, or summaries.

## Updating

This is a snapshot, not a living document. Any update appends a dated change
log entry stating whether it changes a conclusion, raises or lowers
confidence, or merely improves provenance. Never silently rewrite a source
judgment.
