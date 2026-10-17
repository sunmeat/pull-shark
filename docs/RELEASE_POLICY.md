# Release Policy

## Purpose

Pull Shark is primarily a repository-workflow and documentation example. A release should mark a meaningful, stable milestone rather than every merged pull request.

## When to publish a release

Create a GitHub release when a named snapshot would help users or contributors refer to a stable state of the repository. Routine documentation edits do not require a release.

## Versioning

If the project begins publishing versioned artifacts or a stable interface, adopt a versioning scheme that matches those commitments and document it before relying on it. Until then, do not imply that the repository follows semantic versioning for a software API.

## Preparing a release

1. Review the changes since the previous release, if one exists.
2. Update [CHANGELOG.md](../CHANGELOG.md) with notable changes.
3. Check repository links, Markdown formatting, issue forms, and automation.
4. Confirm that policy documents and examples agree with the current repository.
5. Create a descriptive Git tag and release title only when the milestone is meaningful.
6. Summarize user-relevant changes and known limitations in the release notes.

## Corrections

If a published release contains a serious mistake, prefer a clearly documented corrective release over silently changing the meaning of an existing tag.

## Responsibilities

The maintainer is responsible for deciding whether a release is warranted and ensuring that its notes accurately describe the snapshot.
