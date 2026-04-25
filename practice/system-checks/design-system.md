# Design System — System Check

A System Check for evaluating the consistency, structure, and trustworthiness of a design system.

Use this when:

- the system feels inconsistent or hard to rely on
- components behave differently than expected
- teams are bypassing the system
- the system is growing but not getting clearer

---

## Input Fit

This practice works best when the input is close to the actual design system.

Good inputs include:

- a component library or Storybook that is accessible in the working context
- a design system site with inspectable component examples
- a design system Figma file or design artifact available to the AI tool
- a component repository or package source
- a product surface only when it is directly inspectable from available artifacts

Less reliable inputs include:

- documentation about the system without live examples
- marketing pages
- single pages that describe components without showing how the system behaves

If the input is too far from the system itself, this practice may drift into evaluating documentation rather than the design system.

---

## Entry

Select a real surface where the design system is actively used or defined.

Prefer inputs that are close to the system itself, not just descriptions of it.

Do not try to review the entire system.

Stay close to real usage.

Enter the loop by observing what stands out.

---

## Orientation

Stay at the system level.

Do not try to audit every component.

Follow what feels off.

Pay attention to:

- where the system feels inconsistent
- where similar things behave differently
- where the system breaks its own patterns
- where components are bypassed or reimplemented
- where usage feels heavier than it should

Ignore completeness.

Look for tension.

---

## Engagement

Move through the SWARM loop:

Spot → Weigh → Arrange → Refine → Make

Within each loop, direct attention using prompts like:

Spot:
- Where does this system feel inconsistent?
- What exists that shouldn't?
- What feels obviously missing?

Weigh:
- Which inconsistencies matter most?
- Where is trust in the system breaking?
- What creates the most friction?

Arrange:
- If this system were rebuilt today, what would change?
- What should be unified?
- What should be separated?

Refine:
- What is the smallest change that would improve clarity?
- Where can variation be reduced?

Make:
- Recommend the next loop
- Identify whether the next loop should test a change, inspect a narrower area, or evaluate a possible improvement

Do not force progression.

Use this loop to create pressure for the next one.

---

## Signal Awareness

Signals may appear as:

- repeated inconsistencies across different areas
- patterns of duplication or reimplementation
- parts of the system being ignored
- strong reactions to specific components or patterns
- recurring suggestions for the same change

Weak signals will fade.

Strong signals will repeat.

---

## Exit

Pause when:

- a small number of possible improvements emerge
- one or two tensions feel strong enough to carry into another loop
- this loop has produced enough signal for the next pass

Capture:

- what changed
- what was learned
- what still feels unresolved

Decide whether to:

- test a change
- inspect a narrower part of the system
- run another pass later

---

## Notes

This practice can be scoped:

- full system
- component group, such as buttons or inputs
- specific product surface

Smaller scopes tend to produce stronger signals.
