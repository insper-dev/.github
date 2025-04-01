# Contributing Guidelines

Welcome! 👋 This guide outlines how to contribute effectively to projects under the organization.

Our goal is to simulate real-world collaborative software development using Git, Agile methodologies, and best practices in software engineering.

## 🚀 Getting Started

Before contributing:

1. Fork the repository or clone if you're a member.
2. Read the `README.md` to understand the purpose and setup.
3. Install dependencies and verify that the project builds/runs/tests properly.
4. Create a new branch:  

```bash
git checkout -b feat/your-feature-name
```

## 🧠 Workflow

We follow a **simplified** Gitflow workflow:

- `main`: production-ready code  
- `dev`: current development version  
- `feat/*`: new features  
- `refac/*`: refactoring code to improve style/performance  
- `fix/*`: bugfixes  
- `docs/*`: documentation updates  
- `test/*`: test-related changes  

Always branch from `dev`, and submit Pull Requests (PRs) into `dev`.

## 📝 Commit Messages

Use [Conventional Commits](https://www.conventionalcommits.org):

```
<type>(scope): short description
```

Examples:
- `feat(auth): add OAuth2 login flow`
- `fix(api): handle null pointer in response`
- `docs(readme): update project description`

**Types**:
- `feat` → new feature  
- `fix` → bugfix  
- `docs` → documentation only  
- `style` → formatting, no logic change  
- `refactor` → code restructuring  
- `test` → adding/missing tests  
- `chore` → maintenance tasks  

### 🔗 Referencing Issues

To automatically close related issues when a PR is merged, reference them directly in the commit message or PR description using keywords like:

- `fixes #123`
- `closes #123`
- `resolves #123`

**Example:**
```text
fix(login): redirect after token refresh (fixes #42)
```

You can also mention the issue in the Pull Request description:

```markdown
This PR adds support for dark mode toggle.

Closes #98.
```

For more details, see: [GitHub Docs – Linking a pull request to an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)

## ✅ Pull Requests

- Open PRs from a feature branch to `dev`.
- Link related issues in the PR description.
- Request at least one review before merging.
- PR titles should match Conventional Commits.

## 📦 Issues

Use GitHub Issues to track bugs, tasks, and ideas. Apply appropriate labels:
- `bug`, `enhancement`, `documentation`, `question`, `good first issue`, etc.

## 📚 Documentation

Every project must have:
- `README.md`: overview, installation, usage
- `LICENSE`: use MIT or other suitable open license
- `CONTRIBUTING.md`: copied or linked from this one

## 👥 Collaboration & Roles

We follow Scrum roles where applicable:
- **Scrum Master**: facilitates workflow
- **Product Owner**: manages backlog and priorities
- **Developers**: execute and document features

Projects should use GitHub Projects (Scrum board) to manage tasks.

---

Happy coding! 🎓  
For questions, contact the repository maintainers or [@felipeadeildo](https://github.com/felipeadeildo).