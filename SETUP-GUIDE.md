# 🚀 Setup Guide — Next-Level GitHub Profile

Follow these steps to activate everything (takes ~5 minutes).

## Step 1 — Add the files to your profile repo

Your profile repo is `shehanrandika99/shehanrandika99`. Add these files:

```
shehanrandika99/
├── README.md                          ← replace your old one with the new one
└── .github/
    └── workflows/
        ├── profile-3d.yml             ← generates the 3D contribution graph
        └── snake.yml                  ← generates the snake animation
```

Commit and push everything to the `main` branch.

## Step 2 — Enable workflow permissions

1. Go to your repo → **Settings** → **Actions** → **General**
2. Scroll to **Workflow permissions**
3. Select **"Read and write permissions"** → Save

(Without this, the actions can't commit the generated SVG files.)

## Step 3 — Run the workflows manually (first time)

1. Go to the **Actions** tab of your repo
2. Click **GitHub-Profile-3D-Contrib** → **Run workflow**
3. Click **Generate Snake Animation** → **Run workflow**
4. Wait ~1–2 minutes for both to finish (green tick ✅)

After that, they run automatically every day — no more work needed.

## Step 4 — Refresh your profile

Visit `github.com/shehanrandika99` — you should now see:
- 🌊 Animated gradient wave header & footer
- ⌨️ Typing animation
- 🌐 **3D contribution calendar** (night-rainbow theme in dark mode!)
- 🐍 Snake eating your contributions
- 📊 Tokyo Night themed stats, streak, activity graph & trophies
- 💭 Random dev quote that changes on refresh

## ⚠️ Troubleshooting

- **3D graph / snake shows broken image?** → The workflow hasn't run yet. Do Step 3.
- **Workflow fails with permission error?** → You skipped Step 2.
- **Images look cached/old?** → GitHub caches images for a few minutes; hard-refresh (Ctrl+Shift+R).
- The old `github-readme-streak-stats.herokuapp.com` URL is **dead** — the new README already uses the working `streak-stats.demolab.com` endpoint.
