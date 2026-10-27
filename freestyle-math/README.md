# FreeStyle Math

Website for the FreeStyle Math online research seminar, built as a plain static site for GitHub Pages (no build step).

## Structure

    index.html                 About (home page)
    past-seminars/index.html   Past Seminars
    research/index.html        Research
    references/index.html      References
    contact/index.html         Contact
    home/index.html            Redirects /home to the About page
    assets/style.css           Shared styles

Each page lives in its own folder, so URLs are clean: `/past-seminars`, `/research`, and so on.

## Publish on GitHub Pages

1. Create a repository. For a site at `https://<username>.github.io`, name it `<username>.github.io`. Any other name publishes at `https://<username>.github.io/<repo-name>/`.
2. Upload all of these files to the repository root (including the hidden `.nojekyll` file).
3. In the repository, open Settings > Pages, set Source to "Deploy from a branch", choose `main` and `/ (root)`, and save.
4. The site is live within a minute or two.

## Editing

- Next talk: edit the "Next seminar" box in `index.html`.
- Add a past talk: copy one `<li class="talk">` block in `past-seminars/index.html` and fill it in.
- Replace the placeholder emails (`@example.com`) in `contact/index.html` and `index.html`.
- Colors live at the top of `assets/style.css` (light and dark mode).
