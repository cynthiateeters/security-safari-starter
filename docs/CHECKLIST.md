# Security Safari checklist

Track your progress through the hunt.

## Setup

- [ ] Cloned the repository
- [ ] Ran `npm install`
- [ ] Ran `npm run dev` and verified the app works
- [ ] Deployed to Netlify (site name: `security-safari-YOUR-USERNAME`)
- [ ] Read through the docs in this folder

## The Big Five

Each vulnerability gets its own branch and PR. Use the PR template to document each fix.

- [ ] **Vulnerability 1:** Outdated dependency with CVE
  - [ ] Found it
  - [ ] Branch: `fix/outdated-dependency`
  - [ ] PR created (template filled out) and merged

- [ ] **Vulnerability 2:** Hardcoded secret in source code
  - [ ] Found it
  - [ ] Branch: `fix/hardcoded-secret`
  - [ ] PR created (template filled out) and merged

- [ ] **Vulnerability 3:** Secret in git history
  - [ ] Found it
  - [ ] Branch: `fix/secret-in-history`
  - [ ] PR created (template filled out) and merged

- [ ] **Vulnerability 4:** XSS vulnerability
  - [ ] Found it
  - [ ] Branch: `fix/xss-vulnerability`
  - [ ] PR created (template filled out) and merged

- [ ] **Vulnerability 5:** Code injection vulnerability
  - [ ] Found it
  - [ ] Branch: `fix/eval-injection`
  - [ ] PR created (template filled out) and merged

## Deliverables

- [ ] 5 pull requests created and merged (one per fix, template filled out)
- [ ] README.md rewritten as a real project README
- [ ] REFLECTION.md completed (3 questions answered)
- [ ] Verified all PRs are merged
