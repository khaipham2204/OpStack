# pre-commit Framework
pip install pre-commit
pre-commit install
# GitOps Commit Message Template
#
# Format:
#   <type>(scope): short summary
#
# Example:
#   feat(deploy): upgrade nginx image to v1.21.6
#   fix(terraform): rollback subnet CIDR due to routing issue (#231)
#
# Types:
#   feat     - New infrastructure feature
#   fix      - Bug fix or configuration correction
#   chore    - General maintenance (e.g., version bumps)
#   ci       - Changes to GitLab CI/CD or automation
#   docs     - Documentation-only changes
#   refactor - Structural change without functional difference
