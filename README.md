# People Function Responsibility Map

An interactive dashboard of every responsibility carried by the senior HR leader of a
high-volume fulfillment / distribution site, organized into 13 functional domains with
drill-downs and full-portfolio search. Single self-contained file, no build step, no
dependencies beyond Google Fonts.

## Deploy to GitHub Pages

1. Create a new repository (for example, `hr-responsibility-map`).
1. Add `index.html` to the root of the repository and commit.
1. In the repo, go to **Settings → Pages**.
1. Under **Build and deployment → Source**, choose **Deploy from a branch**.
1. Set the branch to `main` and the folder to `/ (root)`, then **Save**.
1. After a minute, the site is live at
   `https://<your-username>.github.io/<repo-name>/`.

## Using it

- **Left rail:** select any functional domain to drill into its responsibilities.
- **Search bar:** type to filter every responsibility across all domains at once.
- **Print / Export:** produces a clean printable version (and PDF via your browser).

## Customizing

All content lives in the `DOMAINS` array near the top of the `<script>` block in
`index.html`. Each domain has a `code`, `name`, `desc`, and an `items` list of
`[title, description]` pairs. Edit that array to add, remove, or reword responsibilities;
the counts and views update automatically.