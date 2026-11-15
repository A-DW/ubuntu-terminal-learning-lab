# Practice methodology

## My learning workflow

I attempt a whole block, collect relevant commands and output, and submit it for a batch review. I use remediation to address specific gaps without rebuilding work I have already demonstrated.

I allow local documentation. I keep assistance levels separate from task outcomes: an answer can be correct and still be walkthrough-assisted.

## Exercise structure

I use the following A–I structure for each complete exercise pack:

| Part | Contents |
|---|---|
| A | Scenario and objectives |
| B | Execution location, prerequisites and rough practice time |
| C | Deterministic synthetic fixture preparation |
| D | Six to ten numbered practical tasks, normally eight |
| E | Completion checklist with fixed and machine-dependent checks |
| F | Optional progressive hints, separate from the assignment |
| G | Worked walkthrough, clearly marked as solutions |
| H | One submission template for the complete block |
| I | Cleanup boundaries and learning checkpoint |

Preparation creates prerequisites, not the assessed result. My task count and practice estimates are not official examination specifications.

## Evidence and assessment

| Status | Meaning |
|---|---|
| Passed | Observed evidence demonstrates the required result and restrictions |
| Partially complete | Relevant requirements are demonstrated but a gap remains |
| Failed | Evidence demonstrates an incorrect result or a violated restriction |
| Not verified | Evidence is insufficient to establish an outcome |

I record assistance separately as independent, hint-assisted, walkthrough-assisted or not reported. I do not assume a missing assistance declaration means an independent attempt.

I can close a guided learning checkpoint after understanding a correction without claiming that I reran it. I preserve that distinction in my review.

## Evidence integrity

- Keep actual commands and relevant output, including unsuccessful results.
- Label corrected reference examples and expected output explicitly.
- Distinguish initial fixtures, expected final structure and observed workspace snapshots.
- Mark redactions without silently changing technical meaning.
- Do not invent command results, timestamps, machine identities or passing checks.
- Record a later correction as a new checkpoint rather than rewriting an earlier attempt.
- Check function as well as appearance: a directory listing alone may not demonstrate the required behaviour.

## Accepted approaches

I accept alternative valid commands unless a task explicitly assesses a named tool or restriction. A concise solution is useful only if it meets the exact requirements and handles the intended inputs safely.

My reviews identify the smallest meaningful gap, avoid repeating passed work and explain the difference between a conceptual correction and a verified functional result.

## File organisation

I keep assignments, hints, walkthroughs and blank templates separate from personal submissions. When I publish reviewed evidence, I use `attempts/attempt-01/` beneath the relevant block and keep reviews separate from raw transcripts.

An inventory or checkpoint summary is not a substitute for the original evidence file. Files listed as pending import are not presented as already published.

## Commit convention

I use `type(scope): action` for concise, action-oriented commit subjects. Examples:

```text
docs(project): clarify publication boundaries
feat(block-01): add workspace preparation
docs(block-01): preserve reviewed attempt evidence
fix(block-01): correct relative link instructions
```

A documentation commit records a repository change, not proof of a terminal result. I do not rewrite or backdate commits to simulate the chronology of the original exercise.
