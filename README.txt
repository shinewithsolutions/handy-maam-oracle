THE HANDY MA'AM ORACLE — GITHUB PAGES / PWA PACKAGE

Configured specifically for:
https://shinewithsolutions.github.io/handy-maam-oracle/

UPLOAD THESE FILES TO THE ROOT OF THE GitHub REPOSITORY:
- index.html
- manifest.json
- service-worker.js
- icons/ (entire folder)

IMPORTANT:
Do not upload the outer folder itself into the repository. When you open the repository, index.html should be immediately visible at the root.

AFTER UPLOADING:
1. GitHub > repository > Settings > Pages.
2. Source: Deploy from a branch.
3. Branch: main. Folder: / (root).
4. Save and wait for deployment.
5. Visit https://shinewithsolutions.github.io/handy-maam-oracle/
6. On Android Chrome, reload the page. When Chrome considers the PWA installable, the gold “Install App” button inside the app will appear. You may also see Install app / Add to Home screen in Chrome's menu.

IF YOU HAD AN OLDER VERSION INSTALLED/CACHED:
- Open Chrome > Settings > Site settings > All sites > shinewithsolutions.github.io and clear stored data for the site, OR clear browsing data for the site.
- Reopen the GitHub Pages URL and refresh once.
- The service-worker cache is now handy-maam-oracle-v4, which forces the old app shell to be replaced after activation.

IPHONE/IPAD:
Safari uses Share > Add to Home Screen. iOS does not use the Android beforeinstallprompt event, so the in-app Install App button is expected to remain hidden there.
