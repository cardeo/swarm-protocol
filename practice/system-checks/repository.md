# Repository — System Check

A Repository System Check is a single SWARM loop applied to a repo to understand whether its structure, language, and contents support what the repo is trying to become.

Use this when:

- the repo feels unclear or hard to orient inside
- the structure seems to fight the intent
- important pieces feel missing, duplicated, or over-explained
- the repo is growing but not getting clearer
- the task is about the repo itself, not a single known file edit
- interpretation matters more than correctness

---

## Input Fit

This practice works best when the AI tool can inspect the actual repository.

Good inputs include:

- a public repo link the AI tool can access
- a local repo opened in the AI tool
- an uploaded repo or archive
- a repo with readable files, directories, and docs
- a project where structure, naming, and language shape how people or agents understand the work
- a repo that is still becoming something

Less reliable inputs include:

- summaries of a repo without access to the files
- pasted file trees without the files themselves
- isolated files without surrounding structure
- issue lists or task descriptions without the repo itself

If there is a clear correct answer, this probably does not need a System Check.

If the input is too indirect, this practice may drift into evaluating a description of the repo rather than the repo itself.

---

## Entry

Start by giving the AI tool access to the repo.

Use one of:

- a public repo link
- a local repo opened in the AI tool
- an uploaded repo or archive

If the AI tool cannot access the repo directly, provide the file tree and the most important files, then treat the run as partial.

Select the repo or part of the repo you want to understand.

Prefer inputs that are close to the repo itself, not just explanations of it.

Do not try to cover the entire repo.

Stay close to real structure and language.

Enter the loop by observing what the repo appears to be becoming.

---

## Orientation

Stay at the system level.

Do not treat this as a cleanup task, audit, correctness check, or best-practice review.

Follow what feels unclear, tense, duplicated, missing, over-explained, or under-explained.

Pay attention to:

- where the structure supports the repo's intent
- where the structure fights the repo's intent
- where language clarifies or obscures purpose
- where similar things are duplicated or separated without a clear reason
- where important context seems missing
- where the repo feels too early, too rigid, or too loose

Ignore completeness.

Look for tension.

Keep human judgment in control.

---

## Engagement

Move through the SWARM loop:

Spot → Weigh → Arrange → Refine → Make

Within each loop, direct attention using prompts like:

Spot:
- What does this repo appear to be becoming?
- What feels unclear, duplicated, or over-explained?
- What feels missing but important?
- Where does the structure support the intent?
- Where does the structure fight the intent?

Weigh:
- Which tensions matter most?
- What ambiguity is useful, and what ambiguity is creating friction?
- What would confuse a new reader or agent?
- What feels too early, too rigid, or too loose?

Arrange:
- What relationships between files or sections could be clearer?
- What should be grouped, separated, renamed, or left alone?
- What structure would better support the repo's current purpose?

Refine:
- What is the smallest structural or language change that would improve clarity?
- What should stay open instead of being decided too soon?
- What signal is strong enough to carry forward?

Make:
- Apply one or two small changes only if the practitioner chooses to act
- Otherwise, capture the signal and decide the next loop

Do not force progression.

Use this loop to create pressure for the next one.

---

## Signal Awareness

Signals may appear as:

- repeated confusion around the same directory, file, or term
- duplicate concepts appearing in different places
- missing structure that keeps becoming relevant
- language that sounds settled before the repo is ready
- sections that explain too much without clarifying purpose
- strong reactions to a name, grouping, or boundary
- recurring suggestions for the same small change

Weak signals will fade.

Strong signals will repeat.

Follow the strongest signals into additional loops.

---

## Exit

Pause when:

- one or two tensions feel strong enough to carry into another loop
- a small structural or language change seems useful
- this loop has produced enough signal for the next pass

Capture:

- what changed
- what was learned
- what still feels unresolved
- what question should be followed next

Decide whether to:

- make one or two small changes
- inspect a narrower part of the repo
- ask a follow-up question
- run another pass later

Do not treat the check as a complete evaluation.

---

## Notes

This practice can be scoped:

- full repo
- top-level structure
- documentation
- naming and language
- one directory or subsystem
- agent-facing instructions

Smaller scopes tend to produce stronger signals.

A System Check is a start, not a finish.

Use the outcome of the loop to decide where to go next.
