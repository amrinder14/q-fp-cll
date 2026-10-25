CLL Signalling Phases 0–3 — installable web app
================================================

This folder is a complete web app. Put it on any HTTPS web host and anyone with
the link can open it on a phone, tablet or computer, with no sign-in. Visitors
can also add it to their home screen, and it keeps working offline after the
first visit.

Files
-----
index.html               the app (all figures, data, notes and references are inside it)
manifest.webmanifest     name, icons and colours used when it is added to a home screen
sw.js                    offline support (caches the app after the first visit)
icon*.png, icon.svg,
apple-touch-icon.png,
favicon-32.png           app icons

Keep all files together in one folder. The host must serve the site over HTTPS
(all the options below do); home-screen install and offline use need it.


Option A — GitHub Pages (free, permanent link)
-----------------------------------------------
1. Sign in at github.com and create a new repository (for example "cll-phases").
   Set it to Public.
2. On the new repository page choose "uploading an existing file", drag in every
   file from this folder (not the folder itself), and click "Commit changes".
3. Open Settings → Pages. Under "Build and deployment", set Source to
   "Deploy from a branch", choose the branch "main" and the folder "/ (root)",
   then click Save.
4. After a minute or two the site is live at
   https://<your-user-name>.github.io/cll-phases/
   Share that link.

To update later: upload the new index.html (and any changed files) to the same
repository. Visitors get the new version the next time they open the app online.


Option B — Netlify or Cloudflare Pages
--------------------------------------
Both offer drag-and-drop deployment of a folder: Netlify Drop
(app.netlify.com/drop) and Cloudflare Pages ("Upload assets"). Drag this whole
folder in; you will be given an https:// link. A free account is needed to keep
the site and to choose a readable address.


Option C — a university or lab web server
-----------------------------------------
Copy the folder to your web space and share the https:// address of index.html.


Adding the app to a home screen
-------------------------------
iPhone / iPad (Safari):  open the link → Share button → "Add to Home Screen".
Android (Chrome):        open the link → ⋮ menu → "Install app" or "Add to Home screen".
Computer (Chrome/Edge):  open the link → install icon at the right of the address bar.

The installed app opens without browser bars. Every option of the desktop
version is available, including Full screen, Compare (Swipe and Grid), the
colour, transparency and label-size controls, the info panel, the
"What changes" table, Corrections and References.

Gestures on phones and tablets
------------------------------
Pinch or double-tap the figure to zoom; drag to move around; ⤢ shows the whole
cell again. Swipe sideways across an un-zoomed figure to change phase. Tap any
component for its notes (they open in a panel at the bottom, or at the side in
landscape). ⚙ Settings (top right) opens a side panel with all the options,
including Light / Dark / Device theme and animation speed; ⛶ enters full screen.
Full screen opens in landscape by default: on a phone held upright the figure is
turned sideways (on Android the screen is locked to landscape where allowed), so
turn the phone to read it. Tap ⟳ in full screen, or change "Full-screen format"
under ⚙, to keep the figure upright instead.

Note: index.html also works on its own (for example as an e-mail attachment or
opened from a computer's disk); only home-screen install and offline caching
need the hosted folder.
