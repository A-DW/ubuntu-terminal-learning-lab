# Publication checklist

Use this checklist before publishing your own lab evidence, reusing examples or proposing a contribution. It is guidance for repository readers, not a claim that unpublished files have already passed review.

## Check origin and references

- Confirm that you wrote the material or have permission to share it.
- Separate your notes from quoted or adapted third-party material.
- Keep source links that you can identify; do not invent replacements for missing references.
- Mark unresolved references explicitly.
- Do not describe personal exercises as official Canonical exam content.
- Check the applicable licence instead of assuming that public files are unrestricted.

## Review personal information

- Inspect command output, Markdown code blocks, screenshots and configuration snippets.
- Remove or visibly redact passwords, tokens, private keys and password hashes.
- Check account names, hostnames, addresses and paths before sharing them.
- Use consistent placeholders where needed and disclose substitutions in terminal evidence.
- Do not upload VM disks, snapshots, personal SSH directories or whole account databases.
- Keep unreviewed material outside tracked files; do not rely on `.gitignore` to inspect content.

## Preserve technical evidence

- Keep observed commands and output distinct from expected results and solutions.
- Preserve meaningful errors instead of silently correcting a transcript.
- Mark redactions, for example `[REDACTED: private hostname]`.
- Label directory snapshots by checkpoint.
- Do not paste an expected tree as if you captured it on your machine.
- Record whether a correction was actually tested.
- Do not infer a passing functional test from a directory listing alone.

## Check lab safety

- Run practice inside disposable VMs and verify the execution location.
- Inspect exact targets before deleting or changing permissions.
- Verify storage mappings rather than guessing device names.
- Keep recovery access during SSH and privilege-policy exercises.
- Read a script before running it; never run an uploaded transcript as a script.
- Preserve earlier attempts before resetting a workspace.

## Current publication boundaries

My full starting notes and raw Block 1 submissions are not included in this repository yet. Their absence is intentional, not evidence that an inventory or review summary replaces them.

See [sources and attribution](sources-and-attribution.md) for authorship and unresolved references, and the [block index](../blocks/README.md) for actual exercise availability.
