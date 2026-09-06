# Contributing Guidelines

Thank you for considering contributing to this project! To make the contribution process smooth and consistent, please follow the guidelines below.

## Table of Contents
- [Code Style](#code-style)
- [Commit Message Conventions](#commit-message-conventions)
- [Branch Naming](#branch-naming)
- [Pull Request Process](#pull-request-process)
- [Reporting Issues](#reporting-issues)

---

### Code Style
- **Language**: Follow the language‑specific style guides (e.g., PEP 8 for Python, Google Java Style for Java, etc.).
- **Formatting**: Use an automated formatter (e.g., `black` for Python, `prettier` for JavaScript) before committing.
- **Linting**: Ensure the code passes the project's linting rules (`flake8`, `eslint`, etc.).
- **Documentation**: Add or update docstrings/comments for any new public APIs.
- **Tests**: Include unit/integration tests for new functionality and ensure existing tests continue to pass.

---

### Commit Message Conventions
We follow the **Conventional Commits** specification:
```
<type>(<scope>): <subject>

<body>

<footer>
```
- **type**: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`, etc.
- **scope** (optional): a short identifier of the area affected, e.g., `parser`, `ui`.
- **subject**: concise description (max 50 characters, no period).
- **body** (optional): detailed explanation of the change.
- **footer** (optional): breaking changes or issue references, e.g., `BREAKING CHANGE: ...` or `Closes #123`.

Example:
```
feat(parser): add support for CSV input

Allow the parser to read CSV files directly, improving data ingestion.

Closes #42
```

---

### Branch Naming
- Use **feature branches** for new work and **bugfix branches** for fixes.
- Naming convention: `<type>/<short-description>`
  - `feature/awesome-feature`
  - `bugfix/fix-login-bug`
  - `hotfix/critical-crash`
- Keep branch names lowercase and use hyphens (`-`) as separators.

---

### Pull Request Process
1. **Sync**: Ensure your branch is up‑to‑date with `main`.
2. **Push**: Push your branch to the remote repository.
3. **Open PR**: Create a pull request targeting the `main` branch.
4. **Title**: Use a clear, concise title (preferably the same as the commit message subject).
5. **Description**:
   - Brief overview of the change.
   - Reference any related issues (e.g., `Closes #123`).
   - Mention any breaking changes.
6. **Review**: Request review from at least one maintainer.
7. **CI**: Ensure all continuous‑integration checks pass.
8. **Merge**: Once approved and checks pass, squash‑merge the PR.

---

### Reporting Issues
- Use the GitHub Issues tab.
- Provide a clear title and description.
- Include steps to reproduce, expected behavior, and actual behavior.
- Attach logs or screenshots if helpful.

---

Thank you for helping improve this project! If you have any questions, feel free to reach out to the maintainers.
