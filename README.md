# Queue Log

Static web app for recording queue observations (arrivals, waits, service) and comparing with M/M/c theory.

## Deploy on Vercel
Option A (no install): go to https://vercel.com/new, choose "Deploy" with this folder (drag & drop or import from a GitHub repo containing it). No build settings needed; framework preset "Other".

Option B (CLI):
    npm i -g vercel
    cd queue-log
    vercel --prod

When hosted on Vercel, data is saved in each visitor's browser (localStorage). Use Export CSV to share data.
# queue-log
# queue-log
