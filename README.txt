Lesia Biloshytska — Career Portfolio (CMYK / RGB)
=================================================

WHAT THIS IS
A single self-contained web page. No build step, no dependencies.
- View it: open index.html in any modern browser.
- Export to A4 PDF: click "Export to A4 PDF" (or Cmd/Ctrl+P) and choose "Save as PDF".

PUT IT ONLINE (pick one)
- Netlify Drop: drag this folder onto https://app.netlify.com/drop
- GitHub Pages: push this folder to a repo, enable Pages on the main branch.
- Vercel: import the folder, framework preset = "Other".
- Any web host: upload index.html to the web root.

ACCESSIBILITY
Built to WCAG 2.2 AA: semantic HTML, real buttons, native <dialog> for the
reader (keyboard trap + Escape + focus return), visible focus rings on every
control, readable type, and keyboard-only support. See chat summary for the
short list of remaining manual checks.

EDITING
All text lives in the CARDS array near the bottom of index.html (inside <script>).
Each card: color, num, kicker, title, sub, cmyk, rgb, body. Edit there and the
grid, the on-screen reader, and the printable A4 pages all update together.
Set "dark:true" on a card to use dark text on a light background.
