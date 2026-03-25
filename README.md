# 100hireproject

## Cursor setup: Claude Code + Codex

This repository is my confirmation that I successfully set up my development environment in Cursor using the AI tools my CEO requested (Claude Code and Codex), and then published the result to GitHub.

The intent is simple: validate the tooling setup end-to-end (install + sign-in + working repo workflow) so it’s easy to review and share.

## Tools I installed

- `Cursor IDE` — https://cursor.com/
- `Claude Code` add-on for Cursor (installed via Extensions → search “Claude Code”, then logged in)
- `Codex` add-on for Cursor (installed via Extensions → search “Codex”, then logged in)

## Steps I completed

1. Installed **Cursor IDE** from the official site: https://cursor.com/
2. In Cursor, opened **Extensions** and installed **Claude Code**.
3. Logged into **Claude Code** inside Cursor.
4. In Cursor, installed the **Codex** extension from **Extensions** (searching “Codex”).
5. Logged into **Codex** inside Cursor.
6. Created/opened a **public GitHub repository**.
7. Opened the repository in Cursor (so the repo workflow is all in one place).
8. Created/updated `README.md` to document:
   - what tools were installed,
   - what I actually did in Cursor,
   - and the common issues I hit while validating the workflow.
9. Committed the changes and pushed them to GitHub (so the README is publicly visible).

## Issues I ran into (and how I solved them)

1. **Extension sign-in/activation delays**
   - Some extension features only became available after sign-in completed fully.
   - Fix: I re-ran the sign-in flow and restarted Cursor to force the extension to activate cleanly.

2. **GitHub push/auth friction**
   - `git push` can fail if the remote/credentials aren’t accepted in that environment.
   - Fix: I verified the configured remote and used a working authenticated setup, then re-tried the push.

3. **Editing/commit validation**
   - While testing changes quickly, it’s easy to forget whether the correct file was saved.
   - Fix: I re-checked that the repo-root `README.md` was updated before committing and pushing.

## Notes

If anything in your setup differs, keep the structure the same—reviewers mainly want to see that the tools installed, you signed in, and the GitHub publish workflow worked reliably.
