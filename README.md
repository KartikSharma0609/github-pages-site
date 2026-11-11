# Task 6: Host a Static Website with GitHub Pages

**Live site:** https://<your-username>.github.io/github-pages-site/

## What I did
- Created a static site with `index.html` and `style.css`.
- Pushed it to a new GitHub repo.
- Enabled GitHub Pages: Settings -> Pages -> Deploy from branch -> `main` / `(root)`.
- Updated the site by committing and pushing changes, which triggers an automatic redeploy.

## Screenshots
Add images from `screenshots/` here.

## Interview Questions
1. **What is GitHub Pages?** A free GitHub service that hosts static websites directly from a repository.
2. **Can you host dynamic apps?** No. It serves only static files (HTML, CSS, JS). There is no server-side code or database, though client-side JS can call external APIs.
3. **Limits?** Recommended repo size under 1 GB, published site under 1 GB, soft bandwidth limit of 100 GB/month, and 10 builds per hour. Public repos are free; private-repo Pages needs a paid plan.
4. **How do you update the website?** Edit files, then `git add`, `git commit`, `git push` to the published branch. GitHub redeploys automatically in a minute or two.
5. **What happens when you delete the repo?** The site goes offline and the URL stops working.
6. **Default file that loads?** `index.html` in the root of the published folder.
7. **Custom domain?** Yes. Add it under Settings -> Pages -> Custom domain and create DNS records (a CNAME or A records) pointing to GitHub. HTTPS is supported.
