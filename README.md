# MLRS Website

Static site: `index.html` + `img/`. No build step.

## Deploy to Hostinger

**Option A — Git (auto-deploy)**
1. hPanel → Websites → Manage → **Advanced → Git**.
2. Repository: `https://github.com/Mesumraza08-art/garden.git`, branch `main`, install path empty (deploys to `public_html`).
3. Click **Deploy**. Enable auto-deployment to redeploy on every push.

**Option B — File Manager / FTP**
Upload `index.html`, `.htaccess` and the `img/` folder into `public_html`.

`.htaccess` forces HTTPS, sets caching and enables compression.
