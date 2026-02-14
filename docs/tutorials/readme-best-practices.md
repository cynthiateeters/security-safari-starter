# README best practices

A good README helps others (and future you) understand a project quickly.

---

## Essential sections

Every project README should include:

1. **Project name and description** - What does this app do? (1-2 sentences)
2. **Quick start** - How to run it locally
3. **Tech stack** - What tools/frameworks are used

---

## Optional sections

Add these if relevant:

- **Features** - What can users do?
- **Project structure** - Where are key files?
- **Scripts** - What npm commands are available?
- **License** - How can others use this code?

---

## Example structure

```markdown
# Project Name

Brief description of what the app does.

## Quick start

\`\`\`bash
npm install
npm run dev
\`\`\`

Open [http://localhost:5173](http://localhost:5173) in your browser.

## Tech stack

- [Vite](https://vitejs.dev/) - Build tool
- [Tailwind CSS](https://tailwindcss.com/) - Styling
- Vanilla JavaScript

## License

MIT
```

---

## Tips

- **Be concise** - README is a quick reference, not documentation
- **Show, don't tell** - Code examples are clearer than explanations
- **Keep it current** - Update when the project changes
- **Link to details** - Point to docs for deeper info

---

## What NOT to include

- Implementation details (put in code comments)
- Changelog (use git history or CHANGELOG.md)
- Lengthy tutorials (link to separate docs)
