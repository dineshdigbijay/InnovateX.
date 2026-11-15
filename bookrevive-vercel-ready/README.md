# BookRevive: Vercel deployment

Static site, no build step.

1. `index.html` must be at the TOP LEVEL of your GitHub repo (not inside a folder).
2. Vercel: Add New Project -> import repo -> Framework Preset "Other" -> leave Build Command and Output Directory empty -> Deploy.
3. Demo admin login: admin@bookrevive.com / admin123
4. To receive book requests by email: create a free form at formspree.io and paste its URL into REQ_ENDPOINT at the top of js/app.js.
