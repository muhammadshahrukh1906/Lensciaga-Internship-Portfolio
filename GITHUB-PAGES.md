# GitHub Pages deployment

This build is prepared for GitHub Pages project URLs such as:

`https://USERNAME.github.io/REPOSITORY/`

## Deploy

1. Create a GitHub repository.
2. Upload **all files in this folder to the repository root**. Keep `index.html` and `eyeglasses.glb` beside each other.
3. In GitHub open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose your main branch and `/ (root)`, then save.
6. Open the HTTPS GitHub Pages URL GitHub provides.
7. Open **Main Slot 3 → Try on with camera** and allow camera permission.

## Important

- Do not test the camera by opening `index.html` as a `file://` URL.
- GitHub Pages provides HTTPS, which is suitable for browser camera permission.
- The Main Slot 3 try-on model is loaded relative to the current page, so it also works when the site is hosted under `/REPOSITORY/`.
- Camera frames are processed in the browser by the try-on code and are not intentionally uploaded by this portfolio.
