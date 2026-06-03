# SatarkScan Website

## Project Info
- Website for SatarkScan Android app (UPI fraud detection)
- Live at: satarkscan.in
- Hosted on: Cloudflare Workers (static site)
- GitHub repo: https://github.com/G4h0ST98/satarkscan.in.git (branch: master)

## File Structure
- index.html — main landing page
- about.html — about page
- cyber-jagrut.html — cyber awareness hub
- articles/ — scam awareness articles
- favicon/ — favicon files
- wrangler.toml — Cloudflare Workers config
- worker.js — Cloudflare Worker entry point

## Git Push
Always use:
git add -A && git commit -m "message" && git push

Note: satarkscan/ folder (Android app) is gitignored — do not commit it.

## Deployment
Pushing to master auto-deploys via Cloudflare Workers GitHub integration.
