# Using MKDocs in Python projects
This project is a simple example of mkdos usage


### Install

To add mkdocs on the project:
```bash
$ poetry add --dev mkdocs
```

To create the configuration files must be used the command below:

```bash
$ mkdocs new .
INFO     -  Writing config file: ./mkdocs.yml
INFO     -  Writing initial docs: ./docs/index.md
```

### Basic description

To see the possible params you can execute mkdocs command with --help param:

```shell
$ mkdocs --help
Usage: mkdocs [OPTIONS] COMMAND [ARGS]...

  MkDocs - Project documentation with Markdown.

Options:
  -V, --version  Show the version and exit.
  -q, --quiet    Silence warnings
  -v, --verbose  Enable verbose output
  -h, --help     Show this message and exit.

Commands:
  build      Build the MkDocs documentation
  gh-deploy  Deploy your documentation to GitHub Pages
  new        Create a new MkDocs project
  serve      Run the builtin development server
```

More in [Documentation](docs/index.md)