# Agriturismo Violiveto – Local Reference Site

A single-page reference site to plan and organize your move to Italy and agriturismo business at Podere Cerreto (Castel Viscardo, Umbria).

## How to open

- **Option 1:** Double-click `index.html` in Finder to open it in your default browser.
- **Option 2:** From terminal: `open index.html` (macOS) or `xdg-open index.html` (Linux).
- **Option 3:** From the project root: `open web/index.html`

No server or build step required; everything runs locally in the browser.

## Hosting on GitHub Pages

The repo includes a workflow that deploys the `web/` folder to a **gh-pages** branch on every push to `main`. GitHub Pages then serves the site from that branch.

1. **Push the repo to GitHub** (if you haven't already).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **gh-pages**, folder **/ (root)**, then **Save**.
5. Push a commit to `main` (or run the "Deploy to gh-pages branch" workflow from the **Actions** tab). The workflow will create/update the `gh-pages` branch and GitHub will publish the site.

The site will be at **`https://<username>.github.io/<repo-name>/`** (e.g. `https://chrizefan.github.io/violiveto/`). You can add a custom domain under **Settings → Pages** if you want.

If your default branch is `master` instead of `main`, change the workflow trigger in `.github/workflows/deploy-gh-pages-branch.yml` from `branches: [main]` to `branches: [master]`, or rename the branch to `main`.

## What's inside

- **Executive Summary** – KPIs, move date, 10-year advantage, immediate to-dos
- **The Property** – Podere Cerreto details, documents, buyer responsibilities
- **Strategy: Agriturismo** – Why agriturismo vs B&B; tax and grant advantages
- **Financial Planning** – Acquisition costs, renovation budget, 10-year P&L
- **Action Timeline** – Integrated move, residency, and business-launch timeline (click items to mark done)
- **Legal & Compliance** – IAP certification steps, CSR Umbria grants
- **Reference** – Pre/post-closing checklists, key numbers, immigration phases, useful links

Content is based on your *Agriturismo Business Plan & Research* and *Italian Agriturismo Purchase & Relocation* materials. Update the HTML or the in-page data in `<script>` as your plans change.
