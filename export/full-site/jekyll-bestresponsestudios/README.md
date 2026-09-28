# Best Response Studios — Jekyll site

Studio site for Best Response Studios (flagship product: Assume a Can Opener). Built with Jekyll, hosted on GitHub Pages.

- `_layouts/`: default (shell), home, product (drives every product page from front matter), about.
- `_includes/`: header, footer, section-heading, game-card, signup-band — thin Liquid wrappers around the Best Response Studios Design System's components.
- `_products/`: one collection doc per product; `assumeacanopener.md` holds all of the A2CO page's copy as front matter data.
- `assets/css/main.css`: full design-system tokens + component styles, hand-ported from the design system's tokens/components (no build step).

`bundle exec jekyll serve` to preview locally.
