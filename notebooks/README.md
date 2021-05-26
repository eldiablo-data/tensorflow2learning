# Notebook instructions

Use google colab to run tensorflow based notebooks.

## Commit to git
Close PyCharm and other IDEs before a commit to avoid conflicts with the pre-commit hooks.

## Pre-commit hook
The following hooks are active:
- jupyter-nb-clear-output : This hook will remove the outputs of all ipynb files. It is required to remove all outputs before commiting a notebook.
