# AT-BCI Website

View the pages locally:

```sh
uv run mkdocs serve                       # Start the server
uv run mkdocs serve -o                    # Open the pages in a web browser
uv run mkdocs serve -o -a localhost:8001  # Open the pages in a web browser on port 8001
```

Publish the pages:

```sh
uv run mkdocs gh-deploy
```

The published pages are available at:

[https://neuroeng-sapienza.github.io/maadb-exam-instructions/](https://neuroeng-sapienza.github.io/maadb-exam-instructions/)
