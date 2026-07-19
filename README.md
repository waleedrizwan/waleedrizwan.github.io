# waleedrizwan.github.io

Personal portfolio — [waleedrizwan.github.io](https://waleedrizwan.github.io)

Single-page static site. No build step: plain HTML, CSS, and vanilla JS, served
from the `main` branch root via GitHub Pages.

```
index.html      # markup + content
styles.css      # editorial / monochrome theme, light + dark
script.js       # theme toggle, footer year, scroll reveal
assets/         # avatar
```

## Local preview

```sh
python3 -m http.server 8000
# open http://localhost:8000
```

## Analytics

Google Analytics 4 is wired in `index.html`. Replace the two `G-XXXXXXXXXX`
placeholders with your Measurement ID to activate it (or delete the block to
disable).
