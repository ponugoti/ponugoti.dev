# Personal Landing Page
A simple landing page based on an R package developed by [Sean Kross](https://seankross.com/).

## Setup
Follow setup instructions at [@seankross/postcards](github.com/seankross/postcards).

## Build

*These steps are only for my reference*

1. Visit https://posit.cloud/content/2309158.
2. Navigate to `ponugoti_dev` project workspace.
3. Make changes to `Index.Rmd`.
4. Rebuild `index.html` using `rmarkdown::render("index.Rmd")`.
5. Move `index.html` to this repo.
6. ???
7. Profit.

## Maintained static site

The published landing page is the self-contained `index.html` in this repository.
The historical Postcards source is not checked in here; small content updates can
be made directly in `index.html`. Keep both the desktop and mobile text blocks in
sync and preserve the embedded profile image unless a photo change is requested.

- Preview locally with `python3 -m http.server 8765 --bind 127.0.0.1`.
- Check the desktop, small-tablet, and phone layouts before publishing.
- The Resume buttons share the existing `Jesse Ponugoti – Resume.pdf` filename and
  URL. Replace that PDF with the public-safe resume without changing its links.
- Preserve `CNAME`, `.nojekyll`, and the independently deployed `feeform/` app.
- Fetch before editing or publishing, use a normal fast-forward push to `master`,
  and verify the **pages build and deployment** workflow for the exact commit.
