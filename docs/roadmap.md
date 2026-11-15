# Six-block roadmap

I use this roadmap to organise practical preparation. It is my training design, not an official exam blueprint. Each block targets eight practical tasks; future exercise packs will be published one complete block at a time.

## Block 1 — Files and navigation

**Location:** CLIENT. **Scenario:** organise the Project Atlas workspace.

| Task | Focus |
|---|---|
| B1-T1 | Absolute/relative paths, home, parent and previous-directory navigation |
| B1-T2 | Normal/hidden listings, probable types, metadata and viewers |
| B1-T3 | Directories, marker files and exact handover content |
| B1-T4 | Independent attribute-preserving copies, moves and renames |
| B1-T5 | Wildcards, bracket expressions and safe quoting |
| B1-T6 | Hard links, relative symbolic links and rename behaviour |
| B1-T7 | Inspection and narrowly scoped deletion |
| B1-T8 | `find`, optional `locate` and local documentation |

**My learning status:** closed as guided practice with remediation; final verification limits remain explicit. **Publication here:** [checkpoint summary](../blocks/block-01-files-and-navigation/README.md); complete exercise pack and raw evidence not yet imported.

## Block 2 — Text and pipelines

**Location:** CLIENT. **Scenario:** produce reports from controlled logs and delimited account data.

| Task | Focus |
|---|---|
| B2-T1 | stdin/stdout/stderr, overwrite and append |
| B2-T2 | Input redirection and here-documents |
| B2-T3 | Separate/combined capture and redirection order |
| B2-T4 | Pipelines, `tee`, `sort`, `uniq`, `wc` and `cut` |
| B2-T5 | `grep`, regular expressions and exact filtering |
| B2-T6 | `sed`/`awk` transformations with protected originals |
| B2-T7 | `diff`, `cmp` and `comm` |
| B2-T8 | Filename-safe batching with `xargs` or a task-permitted alternative |

**Status:** planned. I will use controlled fixtures with explicit expected counts and report contents. No complete Block 2 exercise is published yet.

## Block 3 — Logs and scheduling

**Location:** SERVER, with console or SSH context specified per task. **Scenario:** investigate activity and automate maintenance.

| Task | Focus |
|---|---|
| B3-T1 | Tagged `logger` event and retrieval |
| B3-T2 | Journal boot, unit, severity and time filters |
| B3-T3 | Active and compressed text logs |
| B3-T4 | Kernel records and permission limits |
| B3-T5 | Lab-specific logrotate policy with isolated state |
| B3-T6 | Cron schedules, environment, paths and permissions |
| B3-T7 | User versus system crontab format; preserve existing entries |
| B3-T8 | Evidence of scheduled execution and captured output |

**Status:** planned. I will not assume that particular system log files or historical events exist.

## Block 4 — Storage

**Location:** SERVER, with execution context specified per task. **Scenario:** prepare disposable application storage.

| Task | Focus |
|---|---|
| B4-T1 | `lsblk`, `blkid`, `df`, `du` and `findmnt` |
| B4-T2 | Create an image and verify its actual loop mapping |
| B4-T3 | Verify target; create a partition table and partition |
| B4-T4 | Create ext4 and inspect label/UUID |
| B4-T5 | Mount, test and unmount |
| B4-T6 | Understand and validate an isolated fstab entry |
| B4-T7 | Check an unmounted filesystem |
| B4-T8 | Safely unmount, detach and tear down |

**Status:** planned. I will never guess the device or target the OS disk. Persistent-mount work must address the backing device's availability; an ephemeral loop entry is not a safe reboot plan.

## Block 5 — Accounts and access

**Location:** SERVER, with execution context specified per task. **Scenario:** separate contributor and auditor access.

| Task | Focus |
|---|---|
| B5-T1 | Identity and account databases |
| B5-T2 | Dedicated test users/groups and memberships |
| B5-T3 | Password lock, ageing, expiry and policy inspection |
| B5-T4 | Ownership and numeric/symbolic permissions |
| B5-T5 | File/directory semantics and umask |
| B5-T6 | Setgid/sticky directories and safe recognition of setuid |
| B5-T7 | ACLs, defaults, masks, backup and restoration |
| B5-T8 | Intended-user allowed/denied checks and cleanup |

**Status:** planned. I will use dedicated test identities rather than modify my administrator identity or blindly change PAM rules.

## Block 6 — SSH and sudo

**Locations:** CLIENT and SERVER, labelled for each step. **Scenario:** establish verified access with limited privileges.

| Task | Focus |
|---|---|
| B6-T1 | Verify SERVER identity through its host-key fingerprint |
| B6-T2 | Generate a dedicated client key without overwriting another key |
| B6-T3 | Deploy only the public key and explicitly test key authentication |
| B6-T4 | SSH client configuration and agent |
| B6-T5 | SSH troubleshooting |
| B6-T6 | Validate syntax and effective server policy before reload |
| B6-T7 | Inspect sudo rights; create and validate a narrow drop-in |
| B6-T8 | Permitted/prohibited tests and recovery checkpoint |

**Status:** planned. I will keep console access and a working SSH session, test a second connection and avoid broad sudo grants or shell escapes.

## Integrated mock

After the six blocks, I plan a fresh integrated mock with explicit dependencies, no visible solutions during the attempt and evidence-based review. It has not been delivered or completed.
