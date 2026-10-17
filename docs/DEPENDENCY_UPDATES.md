# Dependency Update Workflow

Dependency updates can improve security and maintenance, but they should still be reviewed for compatibility.

## Review checklist

- Confirm the package or action being updated is expected and comes from the intended publisher.
- Read the release notes or changelog for breaking changes.
- Check supported runtime versions and compatibility requirements.
- Review the proposed diff and permissions, especially for GitHub Actions.
- Run relevant automated checks and inspect their results.
- Merge only when the update is understood and the checks are satisfactory.

For automated pull requests, do not treat the bot's green status alone as a substitute for reviewing a major-version update.