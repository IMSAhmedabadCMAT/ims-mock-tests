MockTest standalone page
========================
1. index.html is self-contained: the settings (API = your Apps Script /exec URL, AUTH = pin) are at the top of the file. Change them only if you create a new deployment.
2. Upload this whole folder to any static host (Netlify Drop: app.netlify.com/drop, GitHub Pages, Cloudflare Pages, Firebase Hosting...).
3. Share the hosted link with students. Admin page: <link>/?page=admin
4. In Apps Script, redeploy (Deploy > Manage deployments > Edit > New version) so doPost() is live.
