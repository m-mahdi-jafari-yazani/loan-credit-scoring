# Contributing

## Commit Message Format

Each commit message has a type, an optional scope, and a short description:

```
type(scope): short description
```

### Rules

- Use English and the imperative present tense ("add", not "added").
- One logical change per commit.

### Types

| Type | Use for |
|------|---------|
| `feat` | New feature, analysis step, or model |
| `fix` | Bug fix |
| `refactor` | Code restructuring without behavior change |
| `docs` | Documentation |
| `test` | Tests |
| `chore` | Config, dependencies, tooling |

### Examples

```
feat(preprocessing): impute missing income values with median
feat(model): add logistic regression baseline
fix(eval): correct ROC AUC computation
docs: add project structure to README
chore: add data files to .gitignore
```
