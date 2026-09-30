# Manual Test Tool dogfood run

This repository contains a compact manual test suite for the Manual Test Tool.
Each file in `tests/` is a runnable template; the app turns its headings into
sections and its unchecked boxes into test items.

## Set up

1. Push this repository to a Git host.
2. In the app, add it as a repository using its Git URL, branch `main`, and
   template directory `tests`.
3. Sync the repository, then run each template in `tests/`.

Use a disposable second repository entry for deletion checks. Do not delete the
main test-suite entry until you have finished: deleting a repository also
deletes its recorded runs.

Record unexpected behavior in the item's Notes field. The suite is intentionally
brief; skip checks that do not apply to your platform or test data.
