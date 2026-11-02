# Eli Perrett Portfolio

Static portfolio site for eliperrett.com.

The live page is `index.html`. Portfolio media is loaded from the separate `eperrett11/Media` repository through the GitHub contents API.

## Ordering

Edit `portfolio-order.json` to control the portfolio grid:

- `featured`: media paths that stay at the top of the grid
- `hidden`: media paths that should not display
- `shuffleSeed`: change this value to reshuffle all non-featured items
- `metadata`: aspect ratios and optional title/description overrides

New uploaded media appears automatically in the shuffled pool unless it is added to `featured` or `hidden`.

## Repository-hosted images

`localImages` in `portfolio-order.json` lists images stored in this repository. These join the shared gallery pool and use the same metadata, featured ordering, lazy loading, and lightbox as remote media. The four trail renders in `assets/studio/` are full-dimension WebP exports (quality 88), featured at positions 2, 8, 14, and 20 for the studio audience. Keep the gallery loader in `index.html`, `brand/index.html`, and `studio/index.html` synchronized so query-based audience links work too.
