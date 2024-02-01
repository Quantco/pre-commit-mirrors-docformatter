# docformatter pre-commit hook

pre-commit hook of docformatter with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For docformatter: see [here](https://github.com/PyCQA/docformatter)

## Using docformatter with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-docformatter
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: docformatter-conda
```
