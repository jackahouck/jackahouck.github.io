# Jack Houck — Personal Website

A deliberately simple, old-school academic homepage built with one HTML file.

## Files

- `index.html` — the entire website
- `.nojekyll` — prevents GitHub Pages from applying Jekyll processing

## Host it with GitHub Pages

1. Create a new public GitHub repository, such as `jackahouck.github.io`.
2. Upload `index.html` and `.nojekyll`.
3. Open the repository's **Settings**.
4. Go to **Pages**.
5. Under **Build and deployment**, select **Deploy from a branch**.
6. Select the `main` branch and the `/root` folder.
7. Save.

For a repository named `jackahouck.github.io`, the site should appear at:

`https://jackahouck.github.io`

For any other repository name, it should appear at:

`https://jackahouck.github.io/REPOSITORY-NAME/`

## Edit it

Open `index.html` in any text editor. The project links are under the
`Selected Work` heading. Replace or reorder them as needed.

To add a résumé link, place a file named `resume.pdf` beside `index.html`,
then add this inside the contact paragraph:

```html
<span><a href="resume.pdf">Résumé</a></span>
```

The website has no JavaScript, dependencies, build tools, tracking, or analytics.
