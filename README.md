# The Delta Studio

## Workspace Email & Meet Transcript Backup

Automated backup of Google Workspace Gmail inboxes and Meet transcripts for all
domain users, stored in a locked-down Google Shared Drive with a searchable index.

- **Repo:** https://github.com/The-Delta-Studio/full-delta-workspace-backups
- **What it does:** duplicates every backed-up item under both `/Projects/<project>/<user>/`
  and `/Users/<user>/<project>/`, tagged with metadata; runs nightly via GitHub Actions.
- **Search it:** Actions → "Search backups" (or "Read a backed-up item" for one specific
  file) — no local setup needed, just GitHub repo access.
- **Security model & setup:** see the repo's `docs/SECURITY_SETUP.md` and README.
