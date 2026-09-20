# Alan Beraquit — Portfolio

A static portfolio featuring digital-learning experiences, microlearning modules,
curriculum work, and web-development projects.

## Run locally

No build step is required. Open `index.html` directly, or serve the directory:

```sh
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Push the repository to GitHub with `main` as the default branch.
2. In **Settings → Pages**, choose **GitHub Actions** under **Build and deployment**.
3. The included workflow publishes the site on every push to `main`.

The site uses relative links, so it works both as an account site and as a
project site under a repository subpath.
