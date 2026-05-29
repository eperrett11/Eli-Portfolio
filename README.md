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
