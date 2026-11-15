# Block 1 — My learning checkpoint

## Completion decision

I closed Block 1 as guided practice with review and remediation. I understood the remaining corrections and chose to continue rather than repeat the final verification again.

This is not a claim of a clean first-attempt pass or a completely verified final state. Starting a fresh repository does not reopen the learning checkpoint or require resetting my workspace.

## What I practised

I organised a Project Atlas workspace on CLIENT, covering paths, hidden files, probable types, metadata, content viewing, creation, attribute-preserving copies, moves, wildcards, links, safe deletion and discovery.

My initial submission and remediation informed this summary. They are not reproduced here, and this summary is not a live inspection of my VM.

## Remaining verification limits

| Area | What I demonstrated or understood | Limit at closure |
|---|---|---|
| Inspection | Remediation used `file` and `stat` for the missing type/metadata requirements | No remaining inspection gap recorded in the review |
| Copy preservation | A separate fixture showed matching mode/mtime and distinct inodes | The printed comparison status was not preceded by the required content comparison |
| Hard links | Shared inode and document contents were demonstrated | This did not establish symbolic-link correctness |
| Relative symbolic link | I understood that `links/readme` must target `../docs/runbook.txt` for this layout | The submitted link still lacked `../`; a corrected working lifecycle was not resubmitted |

I keep these limits explicit instead of inventing successful output. Corrected reference commands belong in a walkthrough, not silently substituted into my original evidence.

## Lessons I carry forward

- Choose inspection tools for the actual requirement rather than opening every file in an editor.
- Verify copied attributes before later tasks intentionally change the working file.
- Resolve a relative symbolic target from the link's containing directory.
- Check that a link can actually be read; a displayed arrow alone is insufficient.
- Capture the exit status immediately after the command being assessed.
- Use precise filename patterns and inspect exact deletion targets.
- Separate understanding a correction from proving that I reran it successfully.

## Publication status

This repository currently contains only this checkpoint summary for Block 1. The complete reusable exercise pack and raw submissions have not yet been imported here.

The intended evidence candidates are the corrected initial `B1-Submission-template.md` and `B1-Submission-template_remediation.md`. Before publication, I will review personal information, mark substitutions or redactions and preserve technical outcomes.

See the [practice methodology](../../docs/practice-methodology.md), [publication checklist](../../docs/publication-checklist.md) and [block index](../README.md).
