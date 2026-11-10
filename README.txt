DamiDamion JDM Blog — Google Sites compatible build

FILES
- index.html: complete standalone website.
- google_sites_embed.html: code intended for Google Sites > Insert > Embed > Embed code.
- server.py: simple Python HTTP server for preview/hosting.

IMPORTANT GOOGLE SITES LIMITATION
Google Sites can embed HTML/CSS/JavaScript, but it does not become the Python host for this site.
Python can host index.html separately. Google Sites can then embed the hosted URL, or you can paste
the provided embed code into Google Sites.

PYTHON PREVIEW
1. Open Kali/terminal.
2. cd into this folder.
3. Run: python3 server.py
4. Open: http://127.0.0.1:8000

GOOGLE SITES
Option A — paste google_sites_embed.html contents:
Insert > Embed > Embed code > paste the contents > Next > Insert > Publish.

Option B — if the site is hosted publicly by Python-compatible hosting:
Insert > Embed > By URL > paste the public URL.
Google's current help documents both code embeds and URL/full-page embeds.

EMAIL CAPTURE
The included form is deliberately consent-based and uses mailto:damidamion1@gmail.com.
It opens the visitor's email application; it is NOT an automated mailing-list database.
For production email capture, connect the form to a Google Form/Apps Script or a compliant
email platform with consent, unsubscribe and retention controls.

DESIGN
- Ocean blue / red / white palette.
- Black sans-serif typography.
- Japan-inspired visual treatment.
- No business logo has been created.
- Single JDM-focused page; non-JDM/general pages from the previous site are not carried forward.
