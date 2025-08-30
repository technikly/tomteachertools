# Tom's Teacher Tools

A simple static launcher that links to all of my teaching tools. Everything on the page is driven by [`site.yaml`](./site.yaml) – edit that file to add, remove or re-order tools.

## Development

No build step is required. Open `index.html` in a browser or run a simple web server:

```bash
python -m http.server
```

## Editing

Update [`site.yaml`](./site.yaml) with new entries. Each link supports:

- `title` – name of the tool
- `url` – link to navigate to
- `description` – short blurb (optional)
- `icon` – emoji or character shown on the card
- `tags` – list of tags for filtering (optional)

The color theme can be tweaked via the `theme` section in the same file.
