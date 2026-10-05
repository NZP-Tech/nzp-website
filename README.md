# Net Zero Platforms website

**This repository publishes from `/docs`, not from the repository root.**

That is deliberate, and it must stay that way. GitHub Pages serves every file in the
publishing source at a public address, immediately, with no warning and no link needed.
Publishing from the root means every file ever committed here is live on
netzeroplatforms.com.

On 28 September 2026 five files were found publicly readable at the root of this site,
including a client-confidential engagement snapshot and two partner one-pagers. They had
been reachable since June. The site was moved to `/docs` the same day.

## The rules

- Only approved-public website files go in `/docs`.
- Nothing else goes anywhere in this repository. No documents, no one-pagers, no drafts,
  no scripts, no notes, no backups. Client documents belong in the document library behind
  Cloudflare Access, never in a website repository, not even briefly.
- Unlinked is not private. An unguessable address protects nothing.
- After any change, check the live site from outside, signed out.

## Canary

This file is at the repository root. If it ever becomes readable at
https://netzeroplatforms.com/README.md then the publishing source has been switched back
to the root and everything in this repository is public again. That is an incident,
not a niggle. Fix it immediately.
