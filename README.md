# Hermclaw Control Relay

Private relay repository between ChatGPT and the local Hermclaw GitLab Bridge.

## Directories

- `requests/` — commands created by ChatGPT for the local bridge
- `results/` — bridge responses written back after GitLab operations

## Security

Do **not** store GitLab tokens, GitHub PATs, passwords, SSH keys, or other secrets in this repository.
The bridge is expected to restrict GitLab namespaces and writable branch prefixes locally.

Initial bridge version: v0.1.0
