# Stuff

## More stuff

Feeling stuffy?


## Code

Inline `code` like that.

Plain code block:

```
pipx install uv
mkdir explore-mkdocs-material
cd explore-mkdocs-material
uv venv
```

BASH code block:

``` bash
pipx install uv
mkdir explore-mkdocs-material
cd explore-mkdocs-material
uv venv
source .venv/bin/activate
```

Python code block with a title, line numbers, and highlighting:

``` py title="self_destruct.py" linenums="1" hl_lines="7"
#!/usr/bin/env python3

#  This script will self-destruct.

from pathlib import Path

Path(__file__).unlink()
```
