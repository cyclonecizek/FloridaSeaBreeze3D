# Florida east coast sea breeze, 3D trainer

An interactive 3D block diagram of the summer sea breeze on Florida's east coast, from morning initiation through afternoon convection and the collision with the Gulf breeze. Built for training forecasters.

It is a conceptual model, not a forecast. Timing, speeds and depths are typical values for east-central Florida in June through September.

## Files

- `index.html` – the whole app (HTML, CSS and JavaScript in one file)
- `.nojekyll` – tells GitHub Pages to serve the files as-is

## Hosting on GitHub Pages

1. Put these files in the root of a repository (or in a subfolder of an existing Pages repository).
2. In the repository, open Settings, then Pages.
3. Under "Build and deployment", set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. After a minute the page is live at `https://<username>.github.io/<repository>/`.

## Requirements

The page loads three.js r128 from cdnjs and its fonts from Google Fonts, so viewers need internet access and a browser with WebGL.
