# Setup — 3 steps

1. Create a repo named exactly `Muhammad-Ghulam-Ali` (must match your username).
2. Push these two files into it, keeping the folder structure:
   - `README.md`
   - `.github/workflows/snake.yml`
3. Go to **Settings → Actions → General → Workflow permissions** → select **"Read and write permissions"** → Save.
   Then go to the **Actions** tab and manually run "Generate Snake Animation" once (or just push — it auto-runs).

That's it. The snake needs that one workflow run before it shows up (creates an `output` branch with the SVG).

Everything else (stats cards, streak, top languages, typing animation, badges) is already live and needs no setup — they're hosted services pulling your GitHub data in real time.
