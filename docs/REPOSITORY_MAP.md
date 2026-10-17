# Repository Map

This page explains where to find the main guidance and automation in Pull Shark.

## Root files

| Path | Purpose |
| --- | --- |
| `README.md` | Project overview and entry point |
| `CONTRIBUTING.md` | Contribution and pull-request workflow |
| `CODE_OF_CONDUCT.md` | Community expectations |
| `GOVERNANCE.md` | Ownership and decision-making |
| `SECURITY.md` | Private vulnerability reporting guidance |
| `SUPPORT.md` | Help and support routes |
| `CHANGELOG.md` | Notable repository changes |
| `LICENSE` | MIT license terms |
| `CODEOWNERS` | Default ownership and review routing |
| `CITATION.cff` | Software citation metadata |

## GitHub configuration

- `.github/ISSUE_TEMPLATE/` contains structured issue forms.
- `.github/PULL_REQUEST_TEMPLATE.md`, when present, provides a default pull-request checklist.
- `.github/workflows/` contains automated checks and maintenance workflows.
- `.github/dependabot.yml`, when present, configures dependency update proposals.

## Documentation

The `docs/` directory contains supporting guides, including the FAQ, troubleshooting notes, repository map, and decision-record template.

## Keeping this map accurate

When adding or moving a top-level policy, workflow, or documentation guide, update this page in the same pull request if the change affects the map.
