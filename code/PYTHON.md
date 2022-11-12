# Python

## Init Project

We will use poetry. More info on <https://python-poetry.org>.

```bash
poetry init
poetry add --dev black flake8 mypy
```

## Boilerplate

Below is the content of `main.py`.

```python
#!/usr/bin/env python3


def main():
    pass


if __name__ == "__main__":
    main()
```

## Dependencies

The following command installs new dependencies to the project.

```bash
poetry add ...
```

See also <https://python-poetry.org/docs/managing-dependencies>.

## Execution

The following command runs the local code.

```bash
poetry run -- python main.py
```
