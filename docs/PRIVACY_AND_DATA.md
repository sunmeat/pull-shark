# Privacy and Data Handling

## Scope

Pull Shark is a repository for documentation and GitHub workflow examples. This page describes how contributors should handle information in repository content and collaboration. It is not a legal privacy notice for external services.

## Do not commit sensitive information

Never commit or publish:

- Passwords, access tokens, private keys, or other credentials.
- Personal contact details that are not intentionally public and necessary for the project.
- Private messages, confidential documents, or data copied from another service without permission.
- Private vulnerability details before a coordinated disclosure.

Use placeholders in examples, such as `YOUR_TOKEN_HERE`, and explain how a secret should be supplied securely rather than embedding it in a file.

## Issues, pull requests, and logs

Before posting diagnostic output, remove credentials, session identifiers, private URLs, and personal data. Remember that public issues, pull requests, commits, and workflow logs may be visible beyond the immediate contributor group.

If sensitive information is accidentally committed, removing it from the latest file does not necessarily remove it from Git history or copies. Revoke exposed credentials first, then follow the appropriate repository and platform remediation process.

## Data minimization

Request only information that is relevant to understanding a bug or reviewing a change. Issue forms should not ask contributors for sensitive personal details.

## Reporting a concern

For security vulnerabilities, follow [SECURITY.md](../SECURITY.md) and use a private reporting route. For other privacy concerns, contact the maintainer privately through the contact options on the GitHub profile.

## External services

GitHub and any linked third-party services operate under their own policies. This repository does not guarantee how those services process account information, telemetry, or access logs.
