# Contributing to SPCC-CSC-154-Test

Welcome! This guide will help you contribute to our project professionally and collaboratively.

## Ground Rules

- **main is protected** — all work happens on branches and requires a PR with review
- **Issues drive work** — create or claim an issue before starting
- **Be respectful** — treat teammates and feedback with professionalism and kindness

## Workflow

### 1. Create an Issue (or claim an existing one)
Before you start working, create an issue describing what you'll do, or comment on an existing issue to claim it.

### 2. Create a Branch
```bash
git checkout -b <type>/<issue-#>-<short-description>
```

**Branch naming:** Use lowercase, hyphens between words
- `feature/154-add-login-page`
- `bugfix/123-fix-validation-error`
- `docs/88-update-readme`

### 3. Commit Your Work
Write clear, concise commit messages:
```
<type>: <description>

<optional details>
```

**Examples:**
- `feat: add user authentication`
- `fix: resolve null pointer in validator`
- `docs: clarify API endpoint documentation`

**Reference issues:** Include `Closes #<issue-number>` in your commit message when finishing an issue.

### 4. Open a Pull Request
- Link your PR to the issue: write `Closes #<issue-number>` in the PR description
- Add a brief summary of changes
- Request review from your teammates

### 5. Review a PR
- Read the code and linked issue carefully
- Test the changes if possible
- Leave constructive comments
- Approve when satisfied, or request changes
- One approval from a teammate is required before merging

## Questions?
Ask in the PR comments or reach out to the team. We're here to help!