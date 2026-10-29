# L.I.F.E.

Website of L.I.F.E., an experimental scientific education project launched by Gabriel Catren in 2018.

Plain HTML and CSS, no build step. It is published with GitHub Pages.

## Structure

```
index.html              home: about + grid of previous sessions
style.css               the only stylesheet
sessions/*.html         one page per session
images/covers/          cover images used in the home grid
images/<year>/          photographs and publication pages for a session
publications/           PDFs of the collective publications
```

## Editing

- Text: open the HTML file on GitHub, click the pencil icon, edit, then "Commit changes". The site updates within a minute or two.
- New session: copy an existing file in `sessions/`, change its text, then add a card for it at the top of the grid in `index.html` (copy an existing `<li class="card">…</li>` block).
- Photos: upload them to `images/<year>/` (JPG, about 1600 px on the long side), then reference them in the session page.

## Publishing

Settings → Pages → Source: "Deploy from a branch", branch `main`, folder `/ (root)`.
