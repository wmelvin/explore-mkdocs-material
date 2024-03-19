# Stuff

[Setting up the footer - Material for MkDocs](https://squidfunk.github.io/mkdocs-material/setup/setting-up-the-footer/#setting-up-the-footer)

## More stuff

Feeling stuffy?

## Code

Inline `code` like that.

### Plain code block

```
pipx install uv
mkdir explore-mkdocs-material
cd explore-mkdocs-material
uv venv
```

### BASH code block

``` bash
pipx install uv
mkdir explore-mkdocs-material
cd explore-mkdocs-material/
uv venv
. .venv/bin/activate
uv pip install mkdocs-material
uv pip freeze | uv pip compile - -o requirements.txt
code .
mkdocs new .
mkdocs serve
```

Note: Also exploring [uv](https://github.com/astral-sh/uv).


### Python code block

``` py
#!/usr/bin/env python3

#  This script will self-destruct.

from pathlib import Path

Path(__file__).unlink()
```

#### With title, line numbers, and highlighting

``` py title="self_destruct.py" linenums="1" hl_lines="7"
#!/usr/bin/env python3

#  This script will self-destruct.

from pathlib import Path

Path(__file__).unlink()
```
