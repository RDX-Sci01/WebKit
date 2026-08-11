# WebKit / slopkit2

Automatically syncs from [jordyidk/slopkit](https://github.com/jordyidk/slopkit) daily and deploys to GitHub Pages.

## Status

| Workflow | Status |
|---|---|
| Sync | [![Sync slopkit2](https://github.com/RDX-Sci01/WebKit/actions/workflows/sync.yml/badge.svg)](https://github.com/RDX-Sci01/WebKit/actions/workflows/sync.yml) |
| Deploy | [![Deploy website](https://github.com/RDX-Sci01/WebKit/actions/workflows/deploy.yml/badge.svg)](https://github.com/RDX-Sci01/WebKit/actions/workflows/deploy.yml) |

## Manual sync

If you need to sync immediately without waiting for the daily schedule:

1. Click → [![Run Sync](https://img.shields.io/badge/Run%20Sync%20Now-2ea44f?style=for-the-badge&logo=github-actions&logoColor=white)](https://github.com/RDX-Sci01/WebKit/actions/workflows/sync.yml)
2. Click the **Run workflow** dropdown on the right
3. Click the green **Run workflow** button

> Deploy runs automatically after a successful sync.

## How it works

```
jordyidk/slopkit  →  sync.yml (daily @ midnight UTC)  →  slopkit2/  →  deploy.yml  →  GitHub Pages
```

## First time setup

The sync workflow must run at least once before deploy will work:

1. Go to **Actions → Sync slopkit2 → Run workflow**
2. Wait for the green checkmark
3. Deploy triggers automatically
