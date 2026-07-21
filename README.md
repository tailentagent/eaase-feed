# eaase feed

Public mirror for the eaase social pipeline (runs on the homelab box).

- `post-log.json` — every post the pipeline has made, mirrored after each run
- `STATUS.md` — one-line status of the latest run
- Releases → `renders` — MP4 assets that Buffer fetches at publish time. Never delete this release or its assets.

The commit history of this repo is the monitoring surface: each run commits with its status line as the message.