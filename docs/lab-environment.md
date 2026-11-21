# Lab environment

## My two-machine setup

I use two disposable Ubuntu VMs. I identify the execution location in every practical task so I do not confuse my local terminal, the managed VM or the physical host.

| Label | Role | Account convention |
|---|---|---|
| CLIENT | My administration workstation and SSH client | Examples use `client` and `client-machine` as account/hostname placeholders |
| SERVER | My managed Ubuntu machine with an SSH server | The initial access account is `server`; later exercises use dedicated test accounts |

The VMs use KVM's `default` network with dynamically assigned addresses. I do not prescribe an IP address, actual home path or Ubuntu release unless an individual exercise requires one. Placeholder names do not prove the identity of an actual machine.

## Execution locations

I label practical command groups with one of these locations:

- `[CLIENT]`.
- `[SERVER — VM console]`.
- `[SERVER — SSH session]`.

A command entered after an SSH login executes on SERVER. A command copied from an archived submission is evidence to inspect, not an instruction to run blindly.

## Workspace boundaries

I keep repository files separate from generated fixtures. Ordinary file exercises use dedicated directories such as `~/terminal-lab/exam/block1` and `~/terminal-lab/exam/block2` inside the relevant VM.

I run ordinary file work as a normal user. I require explicit targets and justification before privileged changes. No exercise requires changing physical-host storage or networking.

## Recovery and safety

- Use disposable VMs and preserve work before a reset.
- Keep SERVER console access and a known-working session available during SSH or access-policy changes.
- Verify a second login before removing a working authentication method.
- Use verified loop-backed images for storage exercises, not guessed device names or the VM's operating-system disk.

## Local documentation

I allow `man`, shell `help`, `--help` and other local documentation during practice. I record missing optional tools instead of treating their absence as permission to alter the physical host.
