# Core Officer ID Dashboard

A single static page (index.html), with no build step.

## Deploy to Vercel
Option A (Vercel CLI): open a terminal in this folder and run `npx vercel` and then `npx vercel --prod`.
Option B (GitHub): put this folder in a GitHub repo, then in Vercel choose Add New > Project, import the repo,
set Framework Preset to "Other", leave the build command empty, and deploy.

## Updating the data
The data is compiled into index.html. The easiest way to update it is to send the new figures to Claude
and ask for a rebuilt index.html, then replace the file and redeploy.
