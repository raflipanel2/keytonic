# KeyTonic — Website #28

**Planned hostname:** https://keytonic.vercel.app (availability not verified; change every canonical/OG/JSON-LD/sitemap/robots URL if Vercel gives a different domain).

**Publisher email:** raflipanel2@gmail.com
**Google AdSense publisher:** ca-pub-5273146278151587
**ads.txt:** google.com, pub-5273146278151587, DIRECT, f08c47fec0942fa0

## Deployment
1. Unzip this archive; commit its **contents at the repository root** on GitHub (not the enclosing folder).
2. In Vercel, import the repository as a static site with no build command and `.` as root/output directory when necessary.
3. Set the production domain. If not `keytonic.vercel.app`, replace *all* occurrences of `https://keytonic.vercel.app` in HTML, `sitemap.xml` and `robots.txt` before AdSense review.
4. Visit `/`, `/guides/`, `/tools/`, at least three articles, `/ads.txt`, `/sitemap.xml`, `/privacy.html` and `/contact.html` after deployment.
5. Add the live domain to Google Search Console and submit its sitemap. Add the correct domain in the matching Google AdSense account. Verify account eligibility and avoid duplicate publisher accounts contrary to Google policy.
6. Editorial pages embed the AdSense **verification loader once per page**; no manual ad units or promises that ads will serve before Google approval.
7. If you enable personalized ads for users subject to consent requirements, configure a suitable consent mechanism and update Privacy accordingly. The static source itself does not include a CMP.
8. Check links to vendor support pages periodically and update factual instructions for the installed OS/browser versions.

## Site map
- `index.html`: homepage
- `guides/`: 20 evergreen guides
- `updates/`: 2 version-aware editorial notes (not auto-updating news)
- `tools/`: Shortcut Finder, Key Issue Pathfinder, Typing Studio
- `.html` root: About, Contact, Editorial, Sources, Privacy, Terms, Advertising, Categories, 404

## Editorial and safety
Only non-invasive troubleshooting. No permission to log passwords, private keypresses, or upload personal files. The typing studio processes input locally in memory, with no tracking code written by KeyTonic. Google AdSense and Google Fonts are third-party network resources on pages that include them.

## Quality checks
Run a static HTTP server rooted in this directory and test desktop/mobile. The site does not need node/npm, databases or external CSS/JS frameworks. Re-read official support documentation after major browser/OS updates.
