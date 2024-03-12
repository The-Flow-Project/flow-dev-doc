# How to use mkdocs

Mkdocs is a useful tool - based on Python - to create a documentation based on Markdown-Files.
The documentation structure can be pushed to the GitHub repository and after cloning/pulling it, it can be hosted locally.

## Installation

Run `pip install mkdocs` in the terminal.

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

```shell
mkdocs.yml    # The configuration file.
docs/
    index.md  # The documentation homepage.
    ...       # Other markdown pages, images and other files.
```

## Creating new Docs

To create a new doc, which can be found in the sidebar navigation, create a new **md-file** (like *newdoc.md*) in the `docs/`-folder.
Then open the `mkdocs.yml` file and add the new doc in the `nav`-section.

```yaml
nav:
    - Already Existing:existing.md
    - New Doc:newdoc.md
```

## Reading the documentation

After running `mkdocs serve` in the folder of the project documentation folder, go to <http://127.0.0.1:8000>.  

## More

* For a good markdown guide visit [markdownguide.org](https://www.markdownguide.org/).
* For full documentation visit [mkdocs.org](https://www.mkdocs.org).
* To use emojis in Markdown, have a look at this cheatsheet <https://github.com/markdown-templates/markdown-emojis>.
