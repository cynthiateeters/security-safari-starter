# Security Safari instructions

## Your mission

Find the "Big Five" vulnerabilities hidden in this codebase:

1. An outdated dependency with a known CVE
2. A hardcoded secret in the source code
3. A secret lurking in git history
4. An XSS vulnerability
5. A code injection vulnerability

## Before you start

1. Clone your repo and run `npm install`
2. Deploy to Netlify with site name `security-safari-YOUR-USERNAME`

> [!WARNING]
> Deploy before creating PRs to get deploy previews you will need to see.

## How to hunt

Use the guides in the references folder:

- [references/FIELD-GUIDE.md](references/FIELD-GUIDE.md) - Step-by-step hunting instructions
- [references/SPOTTER-TIPS.md](references/SPOTTER-TIPS.md) - How to use AI assistants for security auditing
- [references/KNOW-YOUR-PREY.md](references/KNOW-YOUR-PREY.md) - Understanding AI blind spots

## Deliverables

After completing your hunt, submit:

1. **Five pull requests** - Create a separate branch and PR for each fix:
   - Use the `fix/` prefix (e.g., `fix/xss-vulnerability`)
   - Fill out the PR template to document the vulnerability and fix
   - A security scan runs automatically on each PR (see [tutorials/github-actions.md](tutorials/github-actions.md))
   - Check the deploy preview to verify your fix works (see [tutorials/netlify-previews.md](tutorials/netlify-previews.md))
   - Merge each PR before starting the next fix
   - See [tutorials/git-workflow.md](tutorials/git-workflow.md) for the full workflow

2. **Rewrite README.md** - Transform the README as if this were a real project:
   - Write a brief description of what the app does
   - Include quick start instructions
   - List the tech stack
   - Remove all "intentionally vulnerable" and training exercise language
   - See [tutorials/readme-best-practices.md](tutorials/readme-best-practices.md) for guidance

3. **Complete [REFLECTION.md](REFLECTION.md)** - Answer the three reflection questions about your experience
