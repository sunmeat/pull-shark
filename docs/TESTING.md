# Testing and Validation

Pull Shark is primarily a repository workflow and documentation project. Testing therefore focuses on the validity of documentation, repository configuration, and automation rather than on a nonexistent application runtime.

## Documentation checks

- Review Markdown rendering, heading hierarchy, lists, tables, and code fences.
- Verify relative links against the repository's current file structure.
- Check that commands and examples are clearly identified as examples when they are not intended to be executed.
- Confirm that claims about GitHub behavior are supported by current documentation.

## Configuration checks

- Validate YAML syntax in issue forms and workflow files.
- Review GitHub Actions triggers and permissions.
- Confirm that referenced paths and labels exist.
- Avoid adding secrets or credentials to example configuration.

## Pull-request checks

1. Read the complete diff.
2. Follow changed links and inspect referenced files.
3. Run available automated checks.
4. Review the rendered result on GitHub.
5. Record any checks that could not be run and explain why.

## Future executable code

If scripts or application code are added, introduce appropriate automated tests and document how to run them. Do not add a test framework solely for appearance; choose one that matches the actual technology and risk.

## Interpreting results

A successful test run only covers the checks that were executed. It is not proof that every link, external service, or future platform change will behave as expected.
