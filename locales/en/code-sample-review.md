# Code sample review

A rubric for reviewing a work sample the candidate chooses: existing code they are proud of, or something small written for the occasion. Five criteria, each scored 1–5 against written anchors.

[code-sample-review.csv](code-sample-review.csv) · [worksheet-guide.md](worksheet-guide.md)

## Brief for candidates

- Share code that best represents you as an engineer: something you are proud of, or that took real effort to get working. Firmware, a driver, a control loop or a hardware design also count.
- If nothing existing fits, write something small and new. Spend no more than two to three hours.
- Add a short written explanation: what it does, what made it hard, and what you would change with more time.
- Say plainly which parts are yours and which came from frameworks, tutorials, colleagues or AI tools.
- Embedded and hardware samples: describe what the code talks to (protocol, board, sensors or actuators) and any real-time or resource limits you worked within.
- Diagrams are welcome where they explain how parts relate.
- Submit at least 24 hours before the interview so reviewers can read it beforehand.

## Review criteria

Score 2 or 4 when the sample sits between two anchors.

### C1 · Readability

*Could a teammate follow this on a first read, without the author present?*

- **1:** Needs the author to explain it. Unclear or misleading names, no structure, dead code left in.
- **3:** Followable with effort. Naming is inconsistent; comments describe what the code does rather than why.
- **5:** Reads cleanly. Names carry intent, comments cover only what is not obvious, nothing left lying around.

### C2 · Structure and design judgement

*Are the parts split along sensible boundaries, at an abstraction level that suits the problem?*

- **1:** One large block, or the opposite: layers of indirection for a small problem.
- **3:** A reasonable split, but responsibilities leak across boundaries or the split is mechanical (one file per noun).
- **5:** Boundaries the author can justify. Complexity sits where the real difficulty is.

### C3 · Robustness

*What happens when something goes wrong: bad input, a failing device, a value out of range?*

- **1:** Happy path only. Failures are silent or crash.
- **3:** Some checks, applied unevenly. Errors are detected but swallowed or only logged.
- **5:** Failure modes are considered and handled on purpose, including a stated decision not to handle something.

For embedded and hardware samples, read this as timeouts, sensor dropout, watchdogs, safe-state behaviour and resource limits.

### C4 · Explanation of the difficulty

*Does the explanation name a real constraint and the reasoning that overcame it, or only describe what the code does?*

- **1:** Restates the feature list. "It was hard because it was complex."
- **3:** Names a genuine difficulty, but the solution is asserted rather than reasoned.
- **5:** Names the constraint, the alternatives considered and why this one was chosen. Diagrams, where used, carry the argument.

### C5 · Ownership and honesty

*Is it clear what the author decided, and are they open about what is unfinished?*

- **1:** Boundaries blurred. Framework, tutorial or generated code presented as their own.
- **3:** Their contribution can be identified but is not stated; rough parts are glossed over.
- **5:** States what was theirs and what was given, and names the weakest part with a reason for leaving it.

## Review process

1. Each reviewer reads the sample and scores it independently. Write notes before scores.
2. Record where in the sample each note comes from, so others can check it.
3. Compare scores after everyone has finished. Discuss any criterion where reviewers differ by two or more.
4. Turn low or uncertain scores into interview questions, for example:
   - What was the hardest part, and how did you get past it?
   - Which parts did you write yourself?
   - What would you improve first, and why did you leave it?
   - How did you use AI tools, if at all?
5. Use the scores to prepare the interview, not as a hiring decision on their own.

## Confirm before use

- [ ] Every candidate for the role receives the same brief and time limit.
- [ ] Reviewers agreed the anchors before reading any samples.
- [ ] Scores were given independently and before discussion.
- [ ] Every score has a note pointing to the sample.
- [ ] Follow-up questions are recorded for the interview.

## Limits and decision boundaries

These documents support human review. Agreement does not make a criterion fair, lawful or accurate. Vendor observations are not certification or proof of production quality. Do not publish filled-in worksheets containing candidate or internal business data. The agenda and worksheets are working documents, not claims about application features.

[engineering-screening.md](engineering-screening.md) · [README](README.md)
