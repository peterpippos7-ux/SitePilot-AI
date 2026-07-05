# GitHub Connection and Update Steps

This repo is the open-source home for SitePilot AI.

## Repo

```text
peterpippos7-ux/SitePilot-AI
```

## Local Clone

```bash
git clone https://github.com/peterpippos7-ux/SitePilot-AI.git
cd SitePilot-AI
python -m http.server 8080
```

Open:

```text
http://localhost:8080
```

## Updating the Repo

```bash
git pull
# edit files
git add .
git commit -m "Update SitePilot AI"
git push
```

## Cleaner Update Workflow

```bash
git checkout -b update/construction-pack-v5
# update files
git add .
git commit -m "Update construction pack to v5"
git push -u origin update/construction-pack-v5
```

Then open a pull request.

## GitHub Pages

Go to:

```text
Settings → Pages
```

Set source to:

```text
GitHub Actions
```

The included workflow deploys the static app from `main`.
