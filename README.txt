LOT SIZE CALCULATOR & TRADING JOURNAL - standalone app files

Upload ALL files in this folder to any HTTPS static host (GitHub Pages, Netlify, Cloudflare Pages).
Keep them together in the same folder. Open the hosted link in Chrome, then tap
menu (3 dots) > Install app (or Add to Home screen).

Moving your data from the Claude version:
1. In the Claude version: Journal tab > Backup everything (saves a .json file).
2. In the installed app: Journal tab > Restore backup > pick that .json file.

To update the app later: replace index.html on the host, then change CACHE in sw.js
(e.g. lotcalc-v2) so phones refresh their copy.
