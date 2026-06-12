PT CRAB ARCHIVE - static site
=============================

What this is
------------
A self-contained static website of the PT Crab newsletter, built from the
Ulysses Markdown sheets. 181 issues across the full run (1 through 185; issues
4, 147, 153, and 168 were not in the source). Where an issue had both a free
Blue Crab and a paid King Crab edition, the King Crab/full edition was kept.
Images, promos, subscribe/referral material, and missed-edition/sick notes were
removed. Research-paper links were kept. Issues are ordered newest-first.

Files
-----
index.html      The archive landing page / catalog
styles.css      All styling (pure CSS, no build step, easy to edit)
issues/*.html   One page per issue

Plain HTML and CSS. No server or build tooling. Open index.html to preview.

Editing
-------
All visual styling lives in styles.css (colors and fonts are CSS variables at
the top). Each issue is its own HTML file under issues/ with the article markup
inside <div class="prose">.

Put it online (free)
--------------------
- Netlify Drop: drag this folder onto https://app.netlify.com/drop for an
  instant URL (good for a quick test).
- GitHub Pages or Cloudflare Pages: upload/push this folder for a permanent,
  professional URL. Recommended for sharing with employers.
All three support a custom domain for free if you want one later.
