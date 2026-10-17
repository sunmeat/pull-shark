# Pull Request Workflow Examples

These examples illustrate how to keep changes focused and easy to review. Branch names and file paths are illustrative.

## Example 1: Correct a broken link

**Branch:** `docs/fix-contributing-link`

1. Identify the broken link and confirm the intended destination.
2. Change only the affected link and nearby wording if needed.
3. Open a pull request describing the problem and correction.
4. Verify the rendered link after merging.

## Example 2: Improve an issue form

**Branch:** `github/improve-bug-report-form`

1. Identify which information is missing from bug reports.
2. Update the relevant issue form under `.github/ISSUE_TEMPLATE/`.
3. Validate YAML indentation and required fields.
4. Check that labels and placeholders are accurate.
5. Describe how the change improves the reports maintainers receive.

## Example 3: Update a policy

**Branch:** `docs/update-security-guidance`

1. Explain why the policy needs to change.
2. Check related documentation for contradictory instructions.
3. Make the policy change and update affected links or references.
4. Ask for review when the change affects security, privacy, or contributor expectations.
5. Record the notable change in the changelog if appropriate.

## Example 4: Respond to review feedback

1. Read each review comment and clarify uncertainty before making assumptions.
2. Commit a focused revision that addresses the feedback.
3. Explain any suggestion you did not adopt and why.
4. Re-run relevant checks and request another review if necessary.

## General principle

A good pull request makes it easy to answer three questions: what changed, why it changed, and how the change was checked. Keep unrelated cleanup in a separate pull request.
