NEW IN v48
Default-OFF Merged Match toggle in Core Match & Glitter Rules. Same-type qualifying lines that overlap or touch orthogonally merge into one match worth 1 point. Unique cards determine 4+ power eligibility. Separate and diagonal-only matches remain separate. Bots use the same matching rules.
Verified T shapes, larger connected shapes, separated and different-type matches, OFF behavior, scoring, power awards, bot evaluation, and mobile setup.

NEW IN v47
Adjacent Glitter now uses one Glitter Action button, followed by tapping any firework card.
Counts remain visible as read-only indicators. Animation begins at the tapped card and branches to matching neighbors; its flip also starts first.
Validated actual animation ordering and UI at 1440px, 390px, and 320px. Global targeting unchanged.

BURST v48

OPEN THE GAME
On a desktop, open index.html in a modern browser.
For mobile play and home-screen installation, host this folder on HTTPS
(for example, GitHub Pages), then open its web address on your phone.
Keep index.html, sw.js, manifest.webmanifest, and icons together when hosting.
An offline copy is available after the hosted game has loaded successfully.

CHANGES FROM v45
- Adjacent Glitter and Peony include the tapped center and matching cards
  in the eight surrounding spaces, for humans and bots.
- New default-OFF Crossette Orthogonal (+) setting. OFF retains center plus
  diagonals (X); ON uses center plus orthogonal neighbors (+).
- Shared Crossette targeting for human powers, grid powers, and bot evaluation.
- Crossette artwork rotates 45 degrees to change X to +, keeping its style/color.
- Updated instructions and power names.
- Fixed the undefined round-count reference in Competitive mode.
- Improved narrow-phone settings layout, switch keyboard focus, and player-name
  rendering so typed names are displayed as text.
- Other v45 game defaults retained.

VALIDATION
JavaScript syntax passed. Edge browser checks passed at desktop (1440px)
and emulated mobile widths (390px and 320px), with no page errors or horizontal
overflow. Checked all 25 targeting positions for both Crossette patterns and
adjacent same-type targeting, including edges, corners, and excluded card types.
Action tests covered human/bot Glitter, Peony Clear/Flip, Crossette Clear/Flip
with both patterns, and bot power execution. Action tests isolated random
cascades to verify the original affected cards. Checked all three game modes
with 10 players, round settings, defaults, and final-round power-limit behavior.
Mobile checks use browser emulation; physical iPhone/Android testing is still
recommended before calling this a finished release.
