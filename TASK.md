# Candy Forge — Web Prototype

Build a **playable Match-3 browser game** in a single `index.html` file (inline CSS + JS, no external dependencies).

## Core Requirements

1. **9x9 grid** with 6 candy types (use emoji or colored circles with CSS)
2. **Swap mechanic**: click two adjacent candies to swap; only valid if it creates a match of 3+
3. **Match detection**: horizontal and vertical lines of 3+ same-type candies
4. **Cascade/gravity**: after matches are cleared, candies fall down, new ones spawn from top, check for chain matches
5. **Score system**: 3-match = 100pts, 4-match = 200pts, 5-match = 500pts, cascades get multiplier
6. **Move counter**: start with 30 moves, game over when 0
7. **Visual feedback**: matched candies animate (fade/scale), new candies slide in
8. **Responsive**: works on mobile and desktop
9. **"Forge" theme**: title "Candy Forge: Siege Line", candy colors = weapon-themed (🔴 Fire, 🔵 Ice, 🟢 Poison, 🟡 Lightning, 🟣 Shadow, 🟠 Siege)
10. **Restart button** after game over showing final score

## Technical Constraints

- **Single file**: everything in one `index.html`
- **No frameworks**: vanilla JS + Canvas API or DOM manipulation
- **Smooth animations**: use requestAnimationFrame
- **Touch support**: works on phones
- **Clean code**: well-structured, readable

## Nice to Have (if time permits)

- Sound effects (Web Audio API beeps)
- Special candy for 4-match (bomb that clears area) or 5-match (clears all of one color)
- Combo counter display
- High score saved to localStorage

## Output

Write ONLY `/Users/agislav/.openclaw/workspace/candy-forge-proto/index.html`
