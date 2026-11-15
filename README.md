I build small, dependable automation for personal infrastructure: durable job execution, recoverable backups and command-line tooling that stays out of the way.

### Current work

- **Execution backbone**: a self-hosted workflow coordinator on Debian with leased jobs, approval gates, encrypted backup and restore, and a lightweight pull worker on macOS. Python standard library and SQLite only.
- **creator-os**: one command-line entry point over a set of local content tools, covering health checks, a capability index, spec generation and an evidence-backed ledger.

### Approach

- Reuse what exists before building something new.
- Prefer boring, inspectable parts: SQLite, systemd, plain Python.
- Make every change reversible and every claim testable.

### Stack

Python · SQLite · Shell · systemd / launchd · GitHub Actions · Tailscale

### Contact

Open an issue on any public repository.
