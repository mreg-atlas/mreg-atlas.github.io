# Metabolism Regulation Atlas, next version

This repository is public and builds https://mreg-atlas.github.io, the hidden next version of the Metabolism
Regulation website (user, 2026-11-08): the Atlas and new functions. When the user publishes, its contents are copied
into the official site as one snapshot, and this site stays as the place to try the next round.

Page code only. The map files (`_maps/`, `atlas-data/`, `atlas-downloads/`) are kept in a private repository and put
in only when the site is built (`.github/workflows/build.yml`, one secret, `DATA_TOKEN`), so the site shows
the current files and this repository holds none of them, nor their history. They are ignored here (`.gitignore`);
never commit them.

Names: this repository is public and names no private repository, in files, pages, code comments or commit messages.

- The page code (`_includes/atlas-app.html`, layouts, styles, `meta.html`) is a copy of the Metabolism Regulation
  website's (2026-11-08); a change made there is copied here, and the other way round, until the viewer has one source.
- Hidden: `noindex` on every page, linked from nowhere public.
- After the data change, the workflow is started by hand or by the session that pushed them; a push here starts it too.
- A change counts only when it is live, checked on the site itself.
- The name in full, Metabolism Regulation Atlas, in the site's name, tab title and header (user, 2026-11-08), never
  the short MRegAtlas on the site.
