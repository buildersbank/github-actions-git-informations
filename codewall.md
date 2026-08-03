# Codewall — github-actions-git-informations

GitHub Action composite para expor metadados Git (`action.yml`, `entrypoint.sh`).

- Workflow `check.yml`: análise SonarQube informativa (`continue-on-error` em PR).
- Branch padrão: `master`.
- Job ignorado em PRs de fork (secrets indisponíveis).
