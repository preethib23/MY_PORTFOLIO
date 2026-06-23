Make the portfolio live

Options to publish this static site (choose one):

1) GitHub Pages (recommended)

- Create a GitHub repository (e.g., `USERNAME/portfolio`).
- From the project root run:

```bash
git init
git add .
git commit -m "Initial portfolio"
git branch -M main
# replace USERNAME and REPO with your GitHub account and repo name
git remote add origin git@github.com:USERNAME/REPO.git
git push -u origin main
```

- In the GitHub repo Settings > Pages, choose `main` branch (root) as the source and save. The site will be available at `https://USERNAME.github.io/REPO/`.
- If you want the site at `https://USERNAME.github.io/` use a repo named `USERNAME.github.io`.

Note: If you prefer not to use SSH, use the HTTPS remote URL: `https://github.com/USERNAME/REPO.git`.

2) Netlify (drag & drop or CLI)

- Fast: open https://app.netlify.com/drop and drag the project folder (the built files; here just the repo root) to publish.
- CLI deploy:

```bash
npm install -g netlify-cli
netlify deploy --prod --dir=.
```

3) Vercel

- Install Vercel CLI or connect the GitHub repo in https://vercel.com and deploy (good for static sites).

Notes and tips

- If you want `preethi.html` to be the main page without redirect, rename `preethi.html` to `index.html` (I can do this for you).
- I cannot push to GitHub for you without your credentials — tell me if you want me to create commits locally and provide the exact remote URL, or if you'd like step-by-step help connecting a repository.

Want me to rename `preethi.html` to `index.html` and create a Git commit? Reply "Yes, rename and commit" and provide your preferred commit message (or I will use "Make site ready for deployment").