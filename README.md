# joshtreat.com

One page: who Josh is, the work, the resume, how to reach him. Static HTML, no build step.

Deploy: Cloudflare Pages (free), build output directory `/` (this folder), no build command. Then add the custom domain `joshtreat.com` (and `www`) in the Pages project and set the records GoDaddy needs, or move the domain's nameservers to Cloudflare. If the domain's nameservers move, re-create the iCloud custom-email records (MX, SPF, DKIM) first so @joshtreat.com mail keeps working.

Update: edit `index.html`, replace `Joshua_A_Treat_Resume.pdf` with the latest export from the resume doc, push.
