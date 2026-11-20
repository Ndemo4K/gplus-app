G+ COLLECTOR APP: HOW TO PUT IT ON PHONES

FILES (upload all five, keep them in one folder):
index.html, manifest.webmanifest, sw.js, icon-192.png, icon-512.png

HOST IT FREE ON GITHUB PAGES
1. On github.com create a new repository named gplus-app.
2. Click Add file, Upload files, drag in the five files, then Commit.
3. Go to Settings, Pages. Under Branch choose main and folder / (root). Save.
4. After a minute your address appears, likely https://ndemo4k.github.io/gplus-app/
5. Open that address on a phone once, with network.

INSTALL ON A PHONE
Android (Chrome): menu with three dots, then Install app (or Add to Home screen).
iPhone (Safari): Share button, then Add to Home Screen.
Open the app once from the home screen while online. After that it opens with no network.

UPDATING THE APP
Replace index.html in the repository. Also change gplus-v1 to gplus-v2 (then v3 and so on) in sw.js.
Phones pick up the new version the next time they open it with network.

BEFORE REAL USE
1. The users, apartments and the sign in code inside index.html are demo placeholders. Do not enter real client data until the sync endpoint is connected (SYNC_URL).
2. Records live on each phone until synced. Clearing the browser data or uninstalling deletes unsynced records, so sync often.
