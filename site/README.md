# Website

The public directory is built from the root `README.md`. Edit tool entries there. This folder contains the template, styles, search, and a builder that uses only Python's standard library.

To preview locally, run these commands from the repository root:

```sh
python3 site/build.py
python3 -m http.server 4173 --directory _site
```

Open `http://localhost:4173`. Generated files in `_site` are ignored by Git.

Run the builder checks with:

```sh
python3 -m unittest discover -s site -p 'test_*.py'
```

## Publish with GitHub Pages

1. In the repository's **Settings → Pages**, select **GitHub Actions** under **Build and deployment → Source**.
2. Commit and push the website files to `main`.
3. In **Actions**, wait for the **Website** workflow to finish. If the files are already on `main`, select that workflow and choose **Run workflow** on `main`.
4. Open `https://ilyaspiridonov.github.io/awesome-localization/`.

The workflow builds and tests pull requests and publishes pushes to `main`. Future README changes are included automatically when pushed to `main`. No separate Pages workflow template or `gh-pages` branch is needed.

For a different site address, set `PAGES_URL` when building to update the canonical URL and sitemap. See [GitHub's publishing-source instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Fonts

The site serves local Latin variable fonts: Hanken Grotesk for body text and Unbounded for the wordmark. Both use the SIL Open Font License 1.1. Their copyright notices and full licenses are preserved in [HankenGrotesk-OFL.txt](fonts/HankenGrotesk-OFL.txt) and [Unbounded-OFL.txt](fonts/Unbounded-OFL.txt), from the official Google Fonts sources for [Hanken Grotesk](https://github.com/google/fonts/blob/main/ofl/hankengrotesk/OFL.txt) and [Unbounded](https://github.com/google/fonts/blob/main/ofl/unbounded/OFL.txt). The build copies the fonts and licenses into `_site/fonts`; no font service is needed at runtime.
