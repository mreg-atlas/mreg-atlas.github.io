# Metabolism Regulation Atlas, next version

This repository is public and builds https://mreg-atlas.github.io, the hidden next version of the Metabolism
Regulation website (user, 2026-11-08): the Atlas and new functions. When the user publishes, its contents are copied
into the official site as one snapshot, and this site stays as the place to try the next round.

Page code only. The map files (`_maps/`, `atlas-data/`, `atlas-downloads/`) are kept in a private repository and put
in only when the site is built (`.github/workflows/build.yml`, one secret, `DATA_TOKEN`), so the site shows
the current files and this repository holds none of them, nor their history. They are ignored here (`.gitignore`);
never commit them.

Names: this repository is public and names no private repository, in files, pages, code comments or commit messages.

- The viewer (`_includes/atlas-app.html`, `_includes/atlas-tags.css`) is a copy of the viewer's source
  (https://viewer-source.github.io, since 2026-11-09; `_includes/VERSION` names its commit): never edited here, a change
  is made in the source and copied with its `copy-to-site.sh`. The layouts, styles and `meta.html` are this site's own
  (from the Metabolism Regulation website, 2026-11-08).
- Hidden: `noindex` on every page, linked from nowhere public.
- After the data change, the workflow is started by hand or by the session that pushed them; a push here starts it too.
- A change counts only when it is live, checked on the site itself.
- The name in full, Metabolism Regulation Atlas, in the site's name, tab title and header (user, 2026-11-08), never
  the short MRegAtlas on the site.
- Nothing on the pages says the site is hidden, a next version, a preview or a draft (user, 2026-11-08): such notes
  are for these files, not for the visitor. The menu has no link to the official site (user: it does not belong here). The header (user, 2026-11-09): the name alone, capitalised, in Helvetica Neue light (Comfortaa and small letters tried and not kept), no logo, no subtitle (not in the tab title either); the menu as large as the name; as wide as the viewer, its edges on the viewer's; a thin line across the window where the bar ends, name and menu in the bar's middle. Any text, label or
  note added to a page that the user has not asked for waits for the user's approval before it goes live.
