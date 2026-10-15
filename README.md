# leo-csoka.github.io

## Deploying the site

The `Deploy GitHub Pages` workflow publishes the repository root whenever a
change is pushed to `main`. In the repository's **Settings → Pages**, set
**Build and deployment → Source** to **GitHub Actions**.

To publish changes from a local clone:

```sh
git add index.html page.html style.css README.md .github/workflows/pages.yml
git commit -m "Fix GitHub Pages deployment and site layout"
git push origin main
```

After pushing, check the **Actions** tab and wait for the `Deploy GitHub Pages`
workflow to complete. The page is deployed when that run succeeds.
