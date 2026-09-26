# Maintaining engineering-blogs

This repository is a curated list in `README.md`, divided into companies,
individual/group contributors, and aggregators. Keep entries in the matching
section, preserve the simple list style, and avoid duplicate names or URLs.

There is no application or build/test manifest. For a list change, inspect the
Markdown diff and verify only the changed links against their intended blog
when network access is available. Report redirects or unavailable links without
claiming the whole list was checked. Use `git diff --check` for whitespace;
do not add a toolchain merely to validate a small list edit.

## Completing changes

Follow existing patterns and carry authorized work through the relevant checks,
repairing failures caused by the change. Choose routine implementation details
directly; ask only when missing information materially changes scope or outcome.
For documentation-only edits, check the diff, referenced paths, and command
accuracy rather than starting application runtimes. If a prerequisite blocks a
check, report the exact blocker and continue independent authorized work. Close
with changed paths, checks actually run and results, and remaining unverified
behavior; distinguish commands inspected from commands executed.
