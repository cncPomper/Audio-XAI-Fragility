# Audio XAI Fragility

![PyPI version](https://img.shields.io/pypi/v/Audio-XAI-Fragility.svg)

A project about Audio models and it's fragility

* [GitHub](https://github.com/cncPomper/Audio-XAI-Fragility/) | [PyPI](https://pypi.org/project/Audio-XAI-Fragility/) | [Documentation](https://cncPomper.github.io/Audio-XAI-Fragility/)
* Created by [Piotr Kitłowski](https://github.com/cncPomper) | GitHub [@cncPomper](https://github.com/cncPomper) | PyPI [@pkitlo](https://pypi.org/user/pkitlo/)
* MIT License

## Features

* TODO

## Documentation

Documentation is built with [Zensical](https://zensical.org/) and deployed to GitHub Pages.

* **Live site:** https://cncPomper.github.io/Audio-XAI-Fragility/
* **Preview locally:** `just docs-serve` (serves at http://localhost:8000)
* **Build:** `just docs-build`

API documentation is auto-generated from docstrings using [mkdocstrings](https://mkdocstrings.github.io/).

Docs deploy automatically on push to `main` via GitHub Actions. To enable this, go to your repo's Settings > Pages and set the source to **GitHub Actions**.

## Development

To set up for local development:

```bash
# Clone your fork
git clone git@github.com:your_username/Audio-XAI-Fragility.git
cd Audio-XAI-Fragility

# Install in editable mode with live updates
uv tool install --editable .
```

This installs the CLI globally but with live updates - any changes you make to the source code are immediately available when you run `audio_xai_fragility`.

Run tests:

```bash
uv run pytest
```

Run quality checks (format, lint, type check, test):

```bash
just qa
```

## Author

Audio XAI Fragility was created in 2026 by Piotr Kitłowski.

Built with [Cookiecutter](https://github.com/cookiecutter/cookiecutter) and the [audreyfeldroy/cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage) project template.
