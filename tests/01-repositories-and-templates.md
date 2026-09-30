# Repositories and templates

## Add and sync

- [ ] Add this repository with its Git URL, branch, and template directory `tests`; verify it appears in the repository list.
- [ ] Open the repository and sync it; verify the latest commit is shown and all three Markdown templates appear.
- [ ] Sync again without changing the remote; verify the repository remains usable and no duplicate entry is created.
- [ ] Change the template directory to a nonexistent folder on a disposable repository entry and sync; verify the empty-template warning is clear.

## Discover templates

- [ ] Verify template titles come from each file's first `#` heading and paths identify the correct files.
- [ ] Start this template; verify only the unchecked boxes become test items, grouped under their headings.
- [ ] Verify Markdown files in subfolders are discoverable when the configured template directory includes them.

## Safe repository management

- [ ] Add a second, disposable entry pointing to this same Git repository; cancel its Delete confirmation and verify it remains.
- [ ] Start a run from the disposable entry, then confirm its deletion; verify the entry and its runs disappear while the main entry and its runs remain.
