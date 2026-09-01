# DeepPace-Sim — project site

A single-page static site explaining the motivation behind
[DeepPace-Sim](https://github.com/) (a synthetic 2D hotel booking-pace
benchmark), the general challenges of forecasting hotel demand from
booking-pace (DTA) information, and reference literature.

## Structure

- `index.html` — the page content.
- `style.css` — styling.

No build step, no dependencies.

## Local preview

```sh
python3 -m http.server 8000
```

Then open <http://localhost:8000>.

## Publish with GitHub Pages

1. Push this repo to GitHub.
2. In the repo's Settings → Pages, set the source to the `main` branch, root
   folder.
3. The site will be published at `https://<user>.github.io/<repo>/`.
