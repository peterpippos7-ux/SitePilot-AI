# SitePilot AI

**SitePilot AI** is an open-source, mobile-first construction productivity tool for creating clean project records quickly.

It is designed for site managers, project managers, coordinators, QA teams, and construction AI builders.

## Features

- RFI generator
- ITP / inspection checklist builder
- Defect register
- Site diary
- Trade action tracker
- Programme risk register
- Local browser storage
- Markdown export
- CSV export
- Construction Pack guidance
- AI prompt builder for ChatGPT, Claude, Gemini, or company AI tools
- Progressive Web App support
- GitHub Pages deployment

## Live App

Once GitHub Pages is enabled, the app will be available at:

```text
https://peterpippos7-ux.github.io/SitePilot-AI/
```

## Run Locally

```bash
python -m http.server 8080
```

Open:

```text
http://localhost:8080
```

## Deploy on GitHub Pages

This repo includes a GitHub Actions workflow at:

```text
.github/workflows/pages.yml
```

To deploy:

1. Open the repository on GitHub.
2. Go to **Settings**.
3. Go to **Pages**.
4. Under **Build and deployment**, set **Source** to:

```text
GitHub Actions
```

5. Go to the **Actions** tab.
6. Open **Deploy SitePilot AI to GitHub Pages**.
7. Click **Run workflow**, or push any new change to `main`.
8. When the workflow finishes, open:

```text
https://peterpippos7-ux.github.io/SitePilot-AI/
```

## Use on Phone

After the GitHub Pages link opens on your phone:

### iPhone

1. Open the link in Safari.
2. Tap **Share**.
3. Tap **Add to Home Screen**.
4. Name it **SitePilot AI**.

### Android

1. Open the link in Chrome.
2. Tap the menu.
3. Tap **Install app** or **Add to Home screen**.
4. Open SitePilot AI from the launcher.

## Updating the App

For future updates:

```bash
git clone https://github.com/peterpippos7-ux/SitePilot-AI.git
cd SitePilot-AI
# edit files
git add .
git commit -m "Update SitePilot AI"
git push
```

GitHub Pages will redeploy automatically after changes are pushed to `main`.

## Construction Safety Note

SitePilot AI helps structure construction records. It does **not** replace project specifications, drawings, contracts, engineers, certifiers, superintendents, client directions, statutory requirements, or formal approvals.

Do not invent standards, tolerances, test frequencies, inspection requirements, or authority requirements. Where requirements are not confirmed, mark them as needing formal confirmation.

## Open Source

Contributions are welcome. See `CONTRIBUTING.md`, `ROADMAP.md`, and `docs/OPEN_SOURCE_MAINTENANCE.md`.
