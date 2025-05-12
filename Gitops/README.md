Here's a more visually appealing and well-organized version of your `README.md` content:

```markdown
# Pre-commit Framework

To set up the pre-commit framework, follow these steps:

1. Install pre-commit:
   ```bash
   pip install pre-commit
   ```

2. Install pre-commit hooks:
   ```bash
   pre-commit install
   ```

---

# GitOps Commit Message Template

**Commit Message Format:**
```
<type>(scope): short summary
```

### Example:
- `feat(deploy): upgrade nginx image to v1.21.6`
- `fix(terraform): rollback subnet CIDR due to routing issue (#231)`

### Types:
- **feat**: New infrastructure feature
- **fix**: Bug fix or configuration correction
- **chore**: General maintenance (e.g., version bumps)
- **ci**: Changes to GitLab CI/CD or automation
- **docs**: Documentation-only changes
- **refactor**: Structural change without functional difference
```
