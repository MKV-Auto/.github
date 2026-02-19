<p align="center">
  <img src="../assets/logo.svg" alt="MKV-Auto" width="200" />
</p>

# MKV-Auto

**Self-hosted automated disc ripping and media management.** From disc insertion to organized files—with automatic detection, metadata lookup, and flexible transfers.

## Features

- **Automated disc detection** — Optical drives detected when you insert a disc (Blu-ray, DVD, UHD).\
- **MakeMKV integration** — Full disc ripping with progress in the web UI.
- **DiscDB metadata** — Automatic lookup in [TheDiscDB](https://thediscdb.com); when found, metadata is applied automatically.
- **Guided labeling** — For unknown discs, a workflow to attach movie/series and title info.
- **Post-processing** — Rename and organize output for Plex or Jellyfin.
- **Multi-protocol transfer** — Local paths, rsync, SMB, or NFS.
- **Docker-ready** — Single image from [GitHub Container Registry](https://github.com/MKV-Auto/mkv-auto-release/pkgs/container/mkv-auto-release); mount `/data` and your optical drive.

Your data stays on your machines. No cloud dependency.

## Getting started

- **Installation & Docker:** [mkv-auto-release](https://github.com/MKV-Auto/mkv-auto-release) — [Installation guide](https://github.com/MKV-Auto/mkv-auto-release/blob/main/docs/Guides/INSTALLATION.md), [Docker guide](https://github.com/MKV-Auto/mkv-auto-release/blob/main/docs/Guides/DOCKER.md), [Quick start](https://github.com/MKV-Auto/mkv-auto-release/blob/main/docs/Guides/QUICKSTART.md).
- **Releases:** [GitHub Releases](https://github.com/MKV-Auto/mkv-auto-release/releases).

## Contributing

We welcome **issues** as the primary way to contribute.

### Submitting issues

- **Bug reports** — Please open an issue with as much detail as you can: crashes, incorrect behavior, installation issues, or platform-specific problems (e.g. Unraid). Clear reports help improve stability and quality.
- **Suggestions & feedback** — Ideas and feedback are welcome via issues. Not every suggestion will be implemented; design and roadmap decisions remain with the maintainers.

**Where to open issues:** [GitHub Issues for mkv-auto-release](https://github.com/MKV-Auto/mkv-auto-release/issues).

### What we don’t accept

- **Pull requests / code contributions** — This project does not accept external code contributions. Development is centralized; pull requests may be closed without review.
- **Redistribution of modified builds** — You may fork and modify the code for your own use under the license; please do not redistribute modified versions or present them as official.

### Security

If you believe you’ve found a security vulnerability, **do not open a public issue.** Follow the instructions in **[SECURITY.md](https://github.com/MKV-Auto/mkv-auto-release/blob/main/SECURITY.md)** in the release repository.

### Full guidelines

For full contribution and conduct details, see **[CONTRIBUTING.md](https://github.com/MKV-Auto/mkv-auto-release/blob/main/CONTRIBUTING.md)** in the [release repo](https://github.com/MKV-Auto/mkv-auto-release).

---

*Self-hosted. Source available. Built for the disc preservation community.*
