# Troubleshooting

This guide covers common problems when working with this repository on GitHub.

## The pull request cannot be merged

- Confirm the pull request targets the intended base branch.
- Review required checks and resolve any failing checks.
- Resolve merge conflicts on the pull request branch.
- Check whether repository rules require reviews or other approvals.

Do not bypass repository protections merely to get a change merged.

## A Markdown check fails

- Read the complete workflow log and identify the file and rule reported.
- Preview the Markdown locally or in GitHub before pushing again.
- Check heading levels, list formatting, trailing whitespace, and link destinations.
- Run the repository's documented checks again after fixing the issue.

## An issue form is unavailable or invalid

- Confirm the YAML file is stored under `.github/ISSUE_TEMPLATE/`.
- Check indentation and required fields.
- Make sure any configured labels already exist in the repository.
- Review the validation output if available.

## A link check reports a failure

- Confirm the destination URL is correct and publicly accessible.
- Prefer stable canonical URLs over temporary redirects.
- For internal documentation, use a relative path that matches the tracked file name.
- If an external service blocks automated requests, document the limitation rather than silently removing a valid link.

## The problem persists

Open an issue with the relevant file, the steps you took, the expected result, and the exact error message. Remove access tokens, passwords, personal data, and other secrets before sharing logs.

For security-sensitive problems, follow [SECURITY.md](../SECURITY.md) instead of opening a public issue.
