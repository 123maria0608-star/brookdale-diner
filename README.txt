BROOKDALE DINER — site rebuild
================================

WHAT'S IN HERE
  index.html   — the entire site, single file. Open it in a browser.

HOW TO PREVIEW LOCALLY
  Double-click index.html. That's it.
  Or run:  open ~/Desktop/brookdale-diner/index.html

THE 90s MUSIC
  The jukebox uses a hidden YouTube iframe. Press the big pink ▶ button
  on the page — browsers block autoplay until the user clicks something.
  The current playlist is a public 90s-hits playlist; if it ever goes
  dead, swap PLAYLIST_ID near the bottom of index.html for any other
  public YouTube playlist ID (the bit after "list=" in the URL).

  This is the legal way to do it — we are not hosting copyrighted MP3s.

WHAT IT INCLUDES
  - Animated neon "BROOKDALE & DINER" sign (flickers like a real one)
  - Live OPEN / CLOSED indicator that reads the actual hours
  - Scrolling marquee at the top
  - Floating burger / shake / pancake emojis
  - 50s checkered dividers between sections
  - Menu cards with hover wiggle + sparkle on click
  - Hours + address + phone + delivery info
  - Working jukebox UI (play / pause / next / prev / mute)
  - Spinning vinyl that pauses when paused
  - Visitor counter (fake, persists per browser — pure 90s)
  - "Under construction" caution-tape ribbon (90s touch)
  - Welcome modal first visit
  - Tap-to-call phone link, tap-to-map address link
  - Konami code easter egg (↑↑↓↓←→←→ B A — try it)
  - Mobile responsive
  - Custom burger cursor

DEPLOY IT (a few free options)
  1) Netlify Drop — drag the brookdale-diner folder onto
     https://app.netlify.com/drop  → instant live URL.
  2) GitHub Pages — push this folder to a repo, enable Pages.
  3) Cloudflare Pages — same idea, drag-and-drop.
  Any of these will give you a live URL to send the diner owner.

ABOUT "STEALING JULIE'S DOMAIN" (brookdalediner.net)
  You can't just take it — it's registered to whoever pays for it
  (Julie or the diner owner). Two normal paths:
   a) The diner owner contacts whoever holds the registration and
      asks them to either point the domain at the new site or
      transfer the domain (registrars do EPP/auth-code transfers).
   b) If the diner owner is paying Wix for it, they log into Wix,
      go to Domains, and either:
        - point DNS at the new host (Netlify etc.), or
        - "transfer out" to a registrar like Cloudflare/Namecheap.
  If Julie is the registrant and won't release it, the diner owner
  can register a new domain (brookdalediner.com is worth checking)
  and point it at the new site instead. ICANN has a dispute process
  for trademark cases too, but that's overkill here.

EDITING THINGS
  All content (hours, menu items, phone, address) lives in index.html.
  Just open it in any text editor and search for what you want to change.
