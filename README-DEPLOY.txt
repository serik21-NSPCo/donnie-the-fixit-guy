Deploying this site to GitHub Pages

1. Create a new GitHub repository. Suggested name: donnie-fix-it-guy-site
2. Upload all files from this folder to the repository root.
3. In GitHub: Settings > Pages
4. Under Build and deployment, set Source to Deploy from a branch.
5. Select Branch: main and Folder: /(root), then Save.
6. Under Custom domain, enter: donniethefixitguy.com
7. In Squarespace DNS, point the domain to GitHub Pages:
   - A records for @ to 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - CNAME for www to <your-github-username>.github.io
8. Wait for DNS and Pages to finish propagating.

Keep the CNAME file in the repository root.
