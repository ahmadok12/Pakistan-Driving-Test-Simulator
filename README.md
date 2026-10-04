# Pakistan Driving Test Simulator

A browser-based driving practice simulator with a 4 m track in a grass field, top follow camera, driver view with side mirrors, mobile steering wheel, forward/reverse pedals, and a Start over button.

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Extract the ZIP and upload **all its files to the repository root** using **Add file → Upload files**. Upload the extracted files, not the ZIP. Commit the upload.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select **main** (or the branch containing your files) and **/(root)**, then **Save**.
6. When deployment finishes, open the website link shown on the Pages settings screen. A project site normally uses `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`.

Official instructions: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Files

- `index.html`: website entry point.
- `style.css`: layout and styling.
- `app.js`: simulator, rendering, and controls.
- `Pakistan-Driving-Simulator.html`: standalone offline version, also used by the website download button.
- `.nojekyll`: serves these static files directly on GitHub Pages.

No build step, npm packages, backend, or API keys are required. Keep the files together. You can also open `index.html` locally, or open the standalone HTML file on its own.

## Controls

- On mobile, drag around the steering wheel rim to turn it naturally.
- Hold Forward or Reverse to move. Releasing Forward applies automatic braking at 2.5 times the previous light-braking rate.
- Use Brake to stop more firmly.
- Switch between the top camera and Driver view.
- Use Start over to reset the session.
- Keyboard: arrow keys to drive, G to switch gear, P to pause.

The interface is designed for landscape use on mobile. This is a practice simulator with approximate tracks; actual licensing tests and requirements can vary.
