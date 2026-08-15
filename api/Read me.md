# Fatimah Job Board server collector
Upload the whole project, not only index.html.
- api/jobs.js: server-side collector
- api/cron.js: daily scheduled endpoint
- vercel.json: daily Vercel Cron
Remotive works without credentials but public listings are delayed 24 hours.
For fresher listings, add Vercel environment variables ADZUNA_APP_ID and ADZUNA_APP_KEY after registering with Adzuna.
The board never submits applications automatically; it opens the original listing for review.
