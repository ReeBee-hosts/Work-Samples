RHEA RAVINDRA — WORK SAMPLES SITE
==================================

CONTENTS
  index.html        The website (open in any browser)
  pdfs/             The five work-sample PDFs the site displays inline

VIEWING LOCALLY
  Double-clicking index.html works, but some browsers block inline PDF
  rendering from local files. To preview exactly as it will appear online,
  run a quick local server from inside this folder:

      python3 -m http.server 8000

  then visit  http://localhost:8000  in your browser.

HOSTING (recommended — PDFs render inline automatically once hosted)
  GitHub Pages:
    1. Create a new repository and upload index.html + the pdfs/ folder
       (keep the folder structure identical).
    2. Settings -> Pages -> deploy from the main branch root.
    3. Your site goes live at https://<username>.github.io/<repo>/

  Netlify (easiest):
    1. Go to app.netlify.com -> "Add new site" -> "Deploy manually".
    2. Drag this entire folder onto the upload area.
    3. Netlify gives you a live URL instantly.

NOTES
  - The TRISEC voyage deck was compressed (3 MB -> 1.2 MB) so the page stays light.
  - Each sample card expands to show the full original PDF in an inline viewer,
    with an "Open full PDF in a new tab" link as a fallback.
  - The Academic Research section has a placeholder ready for future samples.
