# FREEAI — Linear Algebra Website

Static website prepared for GitHub Pages.

## Structure

- `index.html` — homepage
- `applications.html` — applications page
- `careers.html` — careers page
- `simulation/` — three interactive labs
- `.nojekyll` — tells GitHub Pages to publish the files directly

## Publish with GitHub Pages

1. Create a new public GitHub repository.
2. Upload the **contents of this folder** to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.

Your URL will normally be:

`https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Note about notebook buttons

The homepage contains download links for files under `python/*.ipynb`. Those notebook files were not included in the supplied website files, so those download links will return 404 until the notebooks are added in a `python` folder or the links are removed.
