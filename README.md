# Zombddon information pages

Standalone English privacy and support pages, also bundled with the offline iPhone game.
The public app name is **Zombddon**; **ZombieRide** remains the project and working name.
The pages repository name and published URLs remain unchanged.
No build tools, JavaScript, analytics, forms, or external assets are required.

## Publish

1. Create the public GitHub repository `llkenny/zombieride-pages` without initial files.
2. From this directory, publish the existing local commit:

```sh
git push -u origin main
```

3. In the repository Settings → Pages, select **Deploy from a branch**, **main**, and **/(root)**.
4. Wait for deployment and verify both direct URLs:

- https://llkenny.github.io/zombieride-pages/privacy.html
- https://llkenny.github.io/zombieride-pages/support.html

The site root does not have an index page. Use the direct page URLs above.
Use the privacy URL for App Store Connect's Privacy Policy URL and the support URL
for its Support URL. These URLs do not work before GitHub Pages is published.

## Preview and update

Open either HTML file directly in a browser. Relative links work without a server.
Commit and push changes here, then stage this submodule's new commit in the parent
ZombieRide repository. The app bundles the pinned pages; shipping updated bundled
text requires a new app build. Keep public and bundled policies consistent with
actual app data practices. The parent build requires both HTML files.

The maintainer contact is m.s.doroshenko@gmail.com. Hosting uses GitHub Pages;
voluntary support email uses Gmail. Publishing is performed by the maintainer.
