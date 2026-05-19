# Public Releases

Public distribution repository for release binaries and documentation maintained by [Samarth Dubey](https://github.com/iSamarthDubey).

> This repository hosts compiled release artifacts and public-facing documentation only.
> Source code for all projects lives in separate private repositories.

---

## Project Index

> Click on any project name below to view its detailed documentation, installation guides, and changelogs.

| # | Project | Description | Apps | Status |
|---|---------|-------------|------|--------|
| 1 | [Vetan Desk](./projects/vetandesk) | Staff management system for educational institutions | Staff App, Lens Kiosk | Active |

---

## Security

- All release artifacts are signed with official release keystores and built exclusively through automated CI/CD pipelines.
- No user data is collected, transmitted, or stored through this repository.
- Release mirroring from private repositories is handled by authenticated GitHub Actions workflows with asset-level filtering.

## Reporting Issues

This repository is a distribution channel only and does not accept pull requests or feature requests directly. If you encounter a bug, please contact the relevant project's support channel listed in its documentation.

---

## Repository Structure

```
Public/
  README.md                        # This file -- project index
  projects/
    vetandesk/                     # Vetan Desk
      README.md                    # Project overview and app listing
      staff/
        README.md                  # Staff Mobile App -- download, install, requirements
      lens/
        README.md                  # Lens Kiosk App -- download, install, requirements
```

---

*Maintained by [Samarth Dubey](https://github.com/iSamarthDubey)*
