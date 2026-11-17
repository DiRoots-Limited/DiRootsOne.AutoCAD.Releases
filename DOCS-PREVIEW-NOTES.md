# Documentation notes for DiRootsOne.AutoCAD.Releases

Found while testing documentation PR previews on a replica of this repository (`DiRoots-Mauro/DiRoots.Sandbox.AutoCAD.Releases`) and on the production site. None of these items is caused by the preview workflows; they are listed so they can be fixed separately.

## Home page logo is broken in production

`index.md` line 11 references `/assets\images\Commons\DiRootsOne-Revit-Plugin-Logo.png`. This site is served from `https://diroots-limited.github.io/DiRootsOne.AutoCAD.Releases/`, so the leading `/` makes the browser request `https://diroots-limited.github.io/assets/...`, which does not exist. The logo on the home page is missing today.
- Suggested fix: `![DiRootsOne Logo]({{ '/assets/images/Commons/DiRootsOne-Revit-Plugin-Logo.png' | relative_url }})`.

## `CNAME` file points at another product's domain

`CNAME` on `gh-pages` contains `docs.dirootsone.diroots.com`, the domain of the DiRootsOne Revit manual. GitHub Pages ignores it because no custom domain is configured for this repository.
- Suggested fix: remove the file, or replace it with the intended AutoCAD domain and configure that domain in Settings > Pages.
