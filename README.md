poetry-setup hook for pre-commit 
================================

Easy to include hook for poetry-setup and pre-commit.

### Related Items
- pre-commit: https://github.com/pre-commit/pre-commit
- poetry-setup: https://github.com/orsinium/poetry-setup
- poetry: https://github.com/sdispater/poetry

### Using poetry-setup with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
    - repo: https://github.com/mverteuil/precommit-poetry-setup
      rev: master
      hooks:
        - id: poetry-setup
```
