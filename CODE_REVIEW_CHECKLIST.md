# Code Review Checklist

Use this checklist when reviewing a teammate's pull request. Check off items as you go, and leave clear, constructive comments.

---

## ✓ Correctness

- [ ] Does the code do what the issue/PR claims?
- [ ] Are there any obvious bugs or logic errors?
- [ ] Do the tests pass? (check the CI status)
- [ ] Are error cases handled (null checks, empty inputs, etc.)?

---

## ✓ Clarity

- [ ] Are variable and function names clear and descriptive?
- [ ] Is the code easy to follow? (not overly complex)
- [ ] Are there comments where the logic isn't obvious?
- [ ] Is the code consistent with the rest of the project?

---

## ✓ Risk

- [ ] Could this break existing features? (regression risk)
- [ ] Are there edge cases that aren't handled?
- [ ] Does the change affect performance or security?
- [ ] Are dependencies or external services affected?

---

## ✓ Testing & Verification

- [ ] Are there tests for the new code?
- [ ] Do the tests cover happy path *and* error cases?
- [ ] Did you run the tests locally?
- [ ] Is there evidence in the PR that this was tested?

---

## ✓ Documentation

- [ ] Is the README updated (if needed)?
- [ ] Are complex functions documented with comments?
- [ ] Are API changes documented?
- [ ] Are there inline comments for "why," not just "what"?

---

## Example Review Comments

### ✓ Constructive Question
> "I see you're using a for loop here. Would a `.map()` be clearer? Just a suggestion!"

### ✓ Pointing Out a Risk
> "This works for happy path, but what happens if the API returns null? Should we add error handling here?"

### ✓ Praising Good Work
> "Nice refactor! The new function is much more readable, and you added tests for both cases. Approved!"

---

## Before You Approve

- [ ] All checklist items above have been reviewed
- [ ] Any blocking issues have been addressed or discussed
- [ ] You've left at least one meaningful comment (even if just praise!)
- [ ] You understand the change and agree it's ready

---

**Remember:** Be kind and professional. We're all learning!