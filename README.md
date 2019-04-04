# dephell hook for pre-commit _(formerly known as poetry-setup for pre-commit)_

Easy to include hook for dephell and pre-commit.

### Using dephell with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
    - repo: https://github.com/mverteuil/precommit-dephell
      rev: master
      hooks:
        - id: pyproject-toml-to-setup-py
        - id: pyproject-toml-to-requirements-txt
```

You can also configure dephell with `pyproject.toml` and use the bare dephell hook:

```yaml
    - repo: https://github.com/mverteuil/precommit-dephell
      rev: master
      hooks:
        - id: dephell
```

### Related Items
- pre-commit: https://github.com/pre-commit/pre-commit
- dephell: https://github.com/dephell/dephell
- poetry: https://github.com/sdispater/poetry
