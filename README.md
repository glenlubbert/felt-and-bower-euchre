# Felt & Bower — Euchre

A polished, single-file browser game of Euchre. You and your partner North play against West and East, with selectable computer skill levels (Easy / Medium / Hard), realistic card graphics, animations, a live scorecard, on-screen bidding, and an optional Hints coach.

## Play it
The whole game is one file — `index.html`. Just open it in any modern browser, or visit the GitHub Pages link once published (see below).

## How to play
- One suit becomes **trump** through a quick bidding phase before each hand.
- The team that picks trump (the **makers**) must win at least 3 of 5 tricks.
- Jack of trump = **Right Bower** (highest); other Jack of the same color = **Left Bower** (second highest, counts as trump).
- First team to the target score (5 / 10 / 15) wins.

Click **❔ How to play** inside the game for full rules, and **💡 Hints** for suggested plays.

## Publish on GitHub Pages
1. Create a new repository and upload `index.html` (and this `README.md`).
2. Repo **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Choose branch `main`, folder `/ (root)`, then **Save**.
4. Your game goes live at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

No build step, no dependencies — it's plain HTML/CSS/JavaScript.
