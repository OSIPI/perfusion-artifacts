# OSIPI Perfusion Artifacts

This repository hosts a set of example artifacts found in MR perfusion imaging.

## Contributing

You will need to install poetry (a dependency manager) to contribute to this
repository. You can do this by running:

```bash
curl -sSL https://install.python-poetry.org | python3 -
```

This will let you install the dependencies (mkdocs and pre-commit) for this repository
by running (in the environment you want to install the dependencies):

```bash
poetry install
```

To serve the documentation locally, run:

```bash
mkdocs serve
```

You can edit the markdown files in the `docs` folder to update the documentation.

To change the orgnization of the documentation, edit the `mkdocs.yml` file.

To run the pre-commit checks, run:

```bash
pre-commit run --all-files
```

This will let you check if your markdown files are formatted correctly, as well as a
few other checks before you commit your changes. (Intended to catch errors before early)
