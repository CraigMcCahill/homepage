# Craig McCahill Homepage

Static project hub for [craigmccahill.com](https://craigmccahill.com/).

The homepage links to:

- [Ghost Stories](https://craigmccahill.com/ghost-stories/)
- [Urban Explorer](https://craigmccahill.com/urban-explorer/)

## Local preview

Run a static web server from this directory:

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000/>.

## Deployment

Upload the root files, `styles.css`, and `images/` to the document root of
`craigmccahill.com`. Do not replace the existing `ghost-stories/` or
`urban-explorer/` directories.
