MYKO PWA installation launcher

Upload index.html, manifest.webmanifest, sw.js, logo.png, and the icons folder to the ROOT of a GitHub Pages repository. In GitHub Settings > Pages, select Deploy from a branch, main, /(root). Open the resulting HTTPS GitHub Pages URL and choose Install (or Safari > Share > Add to Home Screen).

IMPORTANT: This is an installable LAUNCHER, not a conversion of the Google Apps Script application into an offline or self-contained PWA. Clicking Open MYKO Teacher Workspace navigates to the existing Google Apps Script URL, and the browser/OS may open that address outside the standalone PWA. The original app, login, database and functionality are unchanged. Internet is required for the workspace. Do not put teacher data or credentials into this public repository.

To change the Apps Script deployment URL later, update the href of the link with id="launch" in index.html. To update the launcher, bump the CACHE version in sw.js.
