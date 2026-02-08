# Contributing

## 1. Branching strategy

We use a simplified **Gitflow** model to manage our Ruby on Rails and Ansible codebases.

- **`master`**: Reflects production-ready code deployed on production instances.
- **`develop`**: The main integration branch for the next release.
- **`feature/*`**: Branched from `develop`. Use for feature and issue development.

## 2. Pull request standards

PRs must be descriptive and understandable. Do not use titles and descriptions that make no sense.

### Title conventions

Use **Conventional Commits**:

- `feat:` New features (e.g., `feat: add quiz application for Saudi Arabia`).
- `fix:` Bug fixes (e.g., `fix: direct carrier billing timeout issue`).
- `chore:` Maintenance (e.g., `chore: update Ansible playbooks for web apps`).

### Description requirements

Every PR must explain:

1. **Context**: What does this PR do?

2. **Testing**: How was this tested?

3. **Ticket link**: The ticket link

## 3. Deployment & Quality

- **CI Pipeline**: Every PR triggers a **GitHub CI** check.

- **Code Review**: Provide constructive feedback on every PR to help the team.
