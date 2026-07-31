# 🚀 Setup Guide — New GitHub Profile (5 minutes)

## Step 1 — Replace the README (1 min)

1. Open your profile repo: **github.com/D-Abdullah/D-Abdullah**
2. Edit `README.md` → select all → delete → paste the new `README.md` from this kit → **Commit** to `main`.

Everything except the snake works instantly: typing header, badges, stats cards, streak, featured table, connect row, footer wave.

## Step 2 — Install the snake (2 min)

1. In the same repo: **Add file → Create new file**
2. Name it exactly: `.github/workflows/snake.yml` *(typing the `/` creates the folders)*
3. Paste the contents of `snake.yml` from this kit → **Commit** to `main`.
4. Go to **Settings → Actions → General → Workflow permissions** → select **Read and write permissions** → Save.
5. Go to the **Actions** tab → **generate snake** → **Run workflow** → wait ~40 seconds.

The action creates an `output` branch holding the snake SVGs; the README already points at it. From then on it self-updates daily at midnight UTC.

## Step 3 — Make private work count (1 min, important for you)

Most of your work (BKOTT, BYKII, client projects) is private, so make the activity visible **as anonymous counts**:

- Profile → **Settings → Profile** (or the contribution graph's ⚙️) → enable **"Include private contributions on my profile."**

This feeds your contribution graph, streak, and snake — without exposing any private repo names or code.

## Step 4 — Finishing touches (1 min)

- **Bio** (profile settings) → paste: `Full-Stack Engineer · Node.js · NestJS · Laravel · React · Building e-commerce, ERP & AI automation`
- **Pin** your 4–6 best public repos (Profile → Customize your pins). The featured table's HTML comment shows exactly how to add a public repo row later.
- Confirm the profile repo **D-Abdullah/D-Abdullah is Public** (a private profile repo shows nothing).

## Troubleshooting

| Symptom | Fix |
|---|---|
| Snake image broken ❌ | Step 2.4 permissions not set, or the workflow hasn't run yet — run it manually once from the Actions tab |
| Stats card slow / "unavailable" | Normal — the free Vercel-hosted service throttles at peak; it recovers on its own |
| Streak shows 0 | Enable private contributions (Step 3) |
| Badges not rendering | shields.io hiccup — refresh; they're cached by GitHub's camo proxy after first load |

## What was deliberately removed (consistency with your CV kit)

- ❌ "ITI Java Developer" certification (your instruction: not accurate — now absent everywhere)
- ❌ "Computer Science" education line (your degree is MIS; GitHub profiles don't need an education section, so it's simply omitted)
- ❌ Kubernetes / Jenkins / Deno / neo4j claims (absent from your CVs — GitHub now matches what you can defend in interviews)
- ❌ Public phone number (email + LinkedIn only)
- ❌ Hobbies (your call: all business)
