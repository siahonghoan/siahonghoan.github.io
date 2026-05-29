# Feng-fan Hsieh — Academic Homepage

Personal website of Feng-fan Hsieh (謝豐帆), Graduate Institute of Linguistics, National Tsing Hua University.

## Structure

```
.
├── index.html          # Home
├── publications.html   # Papers
├── talks.html          # Invited talks + upcoming/recent presentations
├── conferences.html    # Full archive of refereed conference presentations
├── styles.css          # Shared stylesheet
└── README.md
```

No build step. Pure HTML + CSS. Fonts are loaded from Google Fonts (Cormorant Garamond, Crimson Pro, Inter Tight).

## Hosting on GitHub Pages

1. Push these files to the root of your repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*.
4. Choose the `main` branch and the `/ (root)` folder, then save.
5. The site will be available at `https://<username>.github.io/<repo>/` within a minute or two. If the repo is named `<username>.github.io`, the site will live at `https://<username>.github.io/`.

## Updating content

All four HTML pages share the same header, footer, and stylesheet, so to add a publication or talk you only need to edit the relevant section in the corresponding `*.html` file. Each entry is a `<p class="entry">…</p>` block. Numbered entries on the talks and conferences pages additionally use `<span class="num">…</span>`.

## License

Content © Feng-fan Hsieh. Markup and styling: feel free to reuse.
