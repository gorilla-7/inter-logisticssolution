# Redirect page

This project is a static HTML page. `index.html` redirects visitors to
`https://google.com`, preserving the URL fragment (the text after `#`).

## Preview

Use Run to start the `Preview site` workflow on port 5000. It copies
`index.html` into `dist/` and serves that directory with Python's built-in
HTTP server. No packages or secrets are required.

## Publishing

Static publishing is configured in `.replit`. The build copies only
`index.html` into `dist/`, the public directory, so repository files are
not published. Click Publish to make the site live.

The preview immediately navigates to Google; Google may prevent its page
from being displayed inside an embedded preview. Open the site in a
separate browser tab to follow the redirect normally.
