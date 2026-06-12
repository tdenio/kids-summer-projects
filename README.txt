MAKER SUMMER — WEBSITE STARTER
==============================

WHAT'S IN THIS FOLDER
---------------------
  index.html    -> the home page (your plan). "index.html" is special:
                   it's the page that loads automatically when someone
                   visits your site, so always name your home page this.
  tracker.html  -> a second page (printable weekly tracker).
  styles.css    -> ALL the styling for every page. Change a color or
                   font here once and every page updates together.

HOW TO PREVIEW IT RIGHT NOW (no internet needed)
------------------------------------------------
  Double-click index.html. It opens in your browser. That's the whole
  site running on your computer. Click the nav links to move between
  pages. (You can stop here if you only want it for yourselves.)

HOW TO ADD A NEW PAGE
---------------------
  1. Copy tracker.html and rename it, e.g. gallery.html
  2. Open it and change the <title> and the content between the
     <div class="sheet"> ... </div> tags.
  3. Add a link to it in the nav bar. The nav is this block near the
     top of EVERY page:

        <div class="links">
          <a href="index.html">The Plan</a>
          <a href="tracker.html">Weekly Tracker</a>
          <a href="gallery.html">Gallery</a>   <-- add this line
        </div>

  4. Paste that same new line into the nav on every page so all pages
     can reach each other. (Static sites copy the nav onto each page —
     for a few pages that's perfectly normal.)

  The "active" class just highlights the page you're currently on —
  move it to whichever link matches that page.

HOW TO PUT IT ON THE INTERNET (free)
------------------------------------
  Easiest — Netlify Drop:
    1. Go to app.netlify.com/drop
    2. Drag this whole folder onto the page.
    3. You get a live web address in seconds. Done.
    (Make a free account to keep it and give it a nicer name.)

  More permanent — GitHub Pages (good if you like version history):
    1. Make a free github.com account.
    2. Create a repository, upload these files.
    3. In the repo: Settings -> Pages -> set the source to your main
       branch. GitHub gives you a public web address.

  To update either one later, just re-upload the changed files.

TIP
---
  The fonts load from Google Fonts over the internet. Hosted online,
  that's automatic. If you open the files offline, the layout still
  works — it just falls back to your computer's built-in fonts.
