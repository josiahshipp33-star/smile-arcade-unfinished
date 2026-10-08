# Toothy Town

Interactive dental games for kids waiting at the dentist. Tap a game card, play Cavity Catch or Brush Blast, and keep every tooth happy.

This is a recreation of the original Toothy Town hub, ready to keep building here.

## Play now

```bash
npm install
npm run dev -- --port 43147
```

Open [http://localhost:43147](http://localhost:43147).

## Single-file version

`public/toothy-town.html` contains the complete hub, Cavity Catch, Brush
Blast, and Smile Match in one editable file. Its styling and JavaScript are included directly
in the HTML, so you can double-click it to open it in a browser without
installing anything.

While the development server is running, view it at
[http://localhost:43147/toothy-town.html](http://localhost:43147/toothy-town.html).

## What’s included

- **Home hub** with the Toothy Town logo and six game cards
- **Cavity Catch** — start screen with how to play, then tap wiggly germs before the 45-second timer runs out. Best score is saved in the browser.
- **Brush Blast** — clean a dirty tooth with three tools: brush plaque to uncover stuck food, blast it, then rinse until it shines.
- **Smile Match** — flip cards to find matching pairs. Each card shows a dental tool and its name, and the board shuffles every round.
- **Coming soon** screens for Floss Run, Sugar Sort, and Smile Art
- Kid-friendly 404 and error pages

## Stack

Next.js, TypeScript, Tailwind CSS, and shadcn/ui.

## Next games to build

- Floss Run — slide floss between teeth to collect stars
- Sugar Sort — sort treats into healthy and not-so-healthy piles
- Smile Art — color and decorate a happy smile
