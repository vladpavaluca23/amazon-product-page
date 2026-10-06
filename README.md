# Amazon Product Page

A recreation of an Amazon book product page, built from scratch with HTML and CSS.
Solo project from the Scrimba "Learn HTML and CSS" course.

**Live:** https://vladpavaluca23.github.io/amazon-product-page/

## Built with

- Semantic HTML
- CSS (no frameworks)
- Flexbox for the two-column layout

## What I practised

- Building a two-column layout with multiple items in each column
- Working from a design spec instead of inventing the layout
- Deploying a static site to the web

## What I learned

- **max-width vs width on images:** `width: 100%` made the book cover fill
  the entire column. Adding `max-width` let it scale down on smaller screens
  while never growing past its intended size.
- **flex: 1 on one column only:** I set `display: flex` on the container and
  `flex: 1` only on the right column, so the left one stays as wide as the
  book cover while the right one takes up the remaining space.
- **Limiting the title width:** without a `max-width`, the title stretched
  across the whole column. I capped it to match the provided design.
- **Deploying with GitHub Pages:** first time putting a page online, straight
  from the repo.

## Credits

- Design, brief and assets: Scrimba
