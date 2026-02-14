# Security Safari instructions

## Your mission

Find the "Big Five" vulnerabilities hidden in this codebase:

1. An outdated dependency with a known CVE
2. A hardcoded secret in the source code
3. A secret lurking in git history
4. An XSS vulnerability
5. A code injection vulnerability

## How to hunt

Use the guides in the references folder:

- [references/FIELD-GUIDE.md](references/FIELD-GUIDE.md) - Step-by-step hunting instructions
- [references/SPOTTER-TIPS.md](references/SPOTTER-TIPS.md) - How to use AI assistants for security auditing
- [references/KNOW-YOUR-PREY.md](references/KNOW-YOUR-PREY.md) - Understanding AI blind spots

## Deliverables

After completing your hunt, submit:

1. **Security audit report** - Document each vulnerability you found, including:
   - What the vulnerability is
   - Where you found it (file and line number)
   - Why it's dangerous
   - How to fix it

2. **Pull request with fixes** - Fork this repository and create a PR that:
   - Fixes all five vulnerabilities
   - Includes clear commit messages explaining each fix
   - A security scan runs automatically and comments on your PR (see [tutorials/github-actions.md](tutorials/github-actions.md))

3. **Update README.md** - Edit the README to reflect that vulnerabilities have been fixed:
   - Remove or update the "intentionally vulnerable" language
   - Update the Safety note section
   - Keep docs in sync with code
