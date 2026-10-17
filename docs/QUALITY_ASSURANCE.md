# Quality Assurance

## Purpose

Quality assurance keeps the repository accurate, navigable, consistent, and safe to contribute to. Checks should match the actual files and workflows in the repository.

## Review dimensions

Before merging a change, consider the following:

- **Correctness:** instructions and examples match current GitHub behavior.
- **Consistency:** terminology, file names, and links agree across documents.
- **Completeness:** the change explains prerequisites, expected outcomes, and important limitations.
- **Accessibility:** headings, links, tables, and examples are understandable without relying on visual cues alone.
- **Security:** no credentials, private data, or unsafe disclosure instructions are introduced.
- **Maintainability:** the change avoids duplication and identifies any related documentation that needs updating.

## Validation

- Inspect the rendered Markdown, not only its source.
- Check relative links and file paths.
- Run the repository's configured automated checks when available.
- Review workflow changes for permissions, triggers, and secret handling.
- Confirm that issue forms and templates use valid YAML and accurate labels.

## Reporting defects

Use the appropriate issue form to report incorrect or outdated guidance. Include the affected path and a concrete example where possible.

## Limitations

A passing automated check does not replace human review. External links and platform behavior can change after a document is merged, so important guidance should be revisited during maintenance.
