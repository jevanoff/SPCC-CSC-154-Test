# Contributing to CSC-154

Welcome to the team! This guide explains how we work together on this project.

---

## Golden Rules

1. **No direct commits to `main`** — all work happens on branches
2. **All changes go through Pull Requests** — even small fixes
3. **Issues drive work** — create or link an issue before starting
4. **Be professional** — respectful, clear communication in all discussions

---

## Branch Naming Conventions

Keep branch names short, descriptive, and lowercase with hyphens.

### Module Practice
```
m2-firstname-lastname        (Module 2 work)
m3-firstname-lastname        (Module 3 work)
```

### Features & Fixes
```
feature-issue-123-short-name      (new feature for issue #123)
fix-issue-456-short-name          (bug fix for issue #456)
```

**Bad:** `my-new-stuff`, `fix`, `issue`  
**Good:** `feature-issue-12-user-login`, `fix-issue-8-null-check`

---

## Commit Messages

Write clear, concise commit messages that explain *why* you made the change.

### Examples

**Good:**
```
Add email validation to signup form (issue #15)

Also updated tests and README with new field requirements.
```

```
Fix off-by-one error in loop (issue #22)

Loop was iterating one extra time, causing duplicate entries.
```

**Bad:**
```
fixed stuff
update
asdf
```

---

## Opening a Pull Request

1. **Create a branch** from `main` following our naming conventions
2. **Make your commits** with clear messages
3. **Push to GitHub** and open a PR with:
   - **Summary:** What did you change? (1–2 sentences)
   - **Linked Issue:** "Closes #123" or "Related to #456"
   - **How Tested:** What did you do to verify it works?
   - **Risks / Notes:** Anything that could break? Any limitations?

4. **Wait for review** — at least one approval before merging

---

## Reviewing a Pull Request

When reviewing a teammate's PR:

1. **Read the summary** — understand what changed and why
2. **Review the code** — check correctness, clarity, and edge cases
3. **Leave at least 2 meaningful comments** — ask questions, suggest improvements, or praise good decisions
4. **Request changes or approve** — be clear about blockers vs. suggestions

### Example Review Comments

**Constructive:**
> "Nice refactor! Consider using a constant for this magic number (5). What happens if the input is empty?"

**Suggesting improvement:**
> "This works, but it might be clearer to extract this logic into its own function. What do you think?"

**Approving:**
> "Looks good! The tests cover the edge cases well, and the naming is clear."

---

## What "Done" Means

A task is complete when:
- ✅ Issue is closed
- ✅ PR is merged to `main`
- ✅ Documentation (README, comments, docs/) is updated if needed
- ✅ No broken tests on `main`

---

## Questions?

Ask in an Issue, in a PR comment, or in Discussions. We're here to help!