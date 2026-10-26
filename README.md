# subash's photography — GitHub Pages + Pages CMS

This is a Jekyll site for GitHub Pages. It includes five original photos. If you have a sixth photo in your currently published version, add it through the editor after setup.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `subash-photography`.
2. Upload the **contents of this ZIP** to the repository root, including `.pages.yml`, `_config.yml`, `_data`, `_photos`, `assets`, and `index.html`. GitHub's browser uploader may hide dotfiles; confirm `.pages.yml` is present.
3. Go to **Settings → Pages → Build and deployment**, choose **Deploy from a branch**, `main`, `/ (root)` and save.
4. After the build completes, open `https://YOURUSERNAME.github.io/subash-photography/`.

## Enable the private editor

1. Visit https://pagescms.org/ and sign in with GitHub.
2. Install/authorize the Pages CMS GitHub app for **only** your `subash-photography` repository (review permissions before approving).
3. Open your repository inside Pages CMS. Its `.pages.yml` config exposes **Website text** and **Gallery photos**.
4. Add a gallery entry, upload a picture, set category and size, then save. Pages CMS commits the changes to GitHub; GitHub Pages rebuilds the live website automatically after the commit.
5. Edit homepage text, hero photo, About text and contact email under **Website text**.

The public website does **not** expose an editing button. Only GitHub users with authorized repository access can edit through Pages CMS. Keep the repository public for free GitHub Pages hosting; do not put private information or secrets in it. Your photos are publicly downloadable.

### Note about photo order
Set `order` as a number (0 first, 1 second, etc.). The hero image is chosen separately under Website text.

### Note about contact
The contact email is blank until you fill it in. There is no backend contact form.

### Important
This Jekyll/Liquid website must be served by GitHub Pages (or Jekyll locally). Double-clicking `index.html` on your computer will display raw template expressions, not the finished gallery.
