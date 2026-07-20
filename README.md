# AMRG — Architectural Management Research Group

Website for the Architectural Management Research Group, Faculty of Architecture, Chulalongkorn University.

## Structure

The whole site is a single self-contained `index.html`:

- One inline `<style>` and one inline `<script>` — no build step, no dependencies
- Images embedded as data URIs
- Bilingual EN/TH, toggled in the header (preference persists in the browser)
- Client-side routing via URL hash (`#/publications`, `#/about/people`, …)

Routes: `home`, `project`, `courses`, `publications`, `resources`, `collaboration`,
`about`, `people`, `person`, `research`, `practice`, `news`.

## Editing

Edit `index.html` directly and commit. GitHub Pages redeploys on push to `main`.

## Local preview

Open `index.html` in a browser, or serve it:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000
