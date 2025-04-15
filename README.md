#### `check-json5`
Attempts to load all json5 files to verify syntax (supports comments, trailing commas, etc.).

- Checks for duplicate keys and invalid JSON5 syntax.
- Uses the [json5](https://pypi.org/project/json5/) python package.

Example usage in your `.pre-commit-config.yaml`:

```yaml
-   repo: https://github.com/doradsoft/json5-pre-commit-hook
    rev: <branch-or-tag-ie-0.0.1>
    hooks:
    -   id: check-json5
```