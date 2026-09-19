# Mayuresh Kadam — Personal Website

Static HTML/CSS/JavaScript portfolio for GitHub Pages. The site is ready for a custom domain such as `www.mayureshkadam.in`.

## Local preview

Open `index.html` directly, or run any local static server from this folder.

## GitHub Pages and GoDaddy

1. Create a GitHub repository and upload the contents of this folder.
2. In **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`.
3. Add a repository file named `CNAME` containing `www.mayureshkadam.in`.
4. In GoDaddy DNS, set `www` as a CNAME pointing to `<your-github-username>.github.io`. Set the root `@` records to GitHub Pages' current A records shown by GitHub.
5. Enable HTTPS after DNS has propagated.

The blog is intentionally file-based so it works without a server. The two example posts can later be replaced or connected to Decap CMS.
