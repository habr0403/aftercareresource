# Minnesota Recovery Meeting Finder

A static, mobile-friendly directory for finding and comparing recovery meetings available to people in Minnesota.

## Included pathways and concerns

The directory includes substance-specific and behavior-specific options for alcohol, drugs, opioids/heroin/fentanyl, methamphetamine, cocaine/crack, cannabis, nicotine/vaping, gambling, food/compulsive eating, sex/love/pornography, internet/technology/gaming/media, spending/debt, work/overactivity, clutter, codependency/relationships, family-of-origin issues, medication-assisted recovery, and family/friend support.

Recovery philosophies include traditional 12-Step, secular/evidence-informed, Buddhist/mindfulness, Christian/faith-based, Indigenous/Wellbriety, medication-friendly, and all-pathways peer support.

## Files

- `index.html` — website structure
- `styles.css` — responsive styling
- `app.js` — search, filters, favorites, modal details, print and CSV export
- `data.js` — recovery resources and meeting terminology

## Run locally

You can double-click `index.html`, or serve the folder with a simple local web server.

Example with Python:

```bash
python -m http.server 8080
```

Then open `http://localhost:8080`.

## Deploy free

This is a fully static site and can be deployed to GitHub Pages, Cloudflare Pages, Netlify, or another static host. No build command is required. Publish the project root.

## Maintenance note

Meeting schedules change frequently. The site intentionally links users to official fellowship meeting finders and Minnesota service bodies instead of hard-coding large schedules. Review the directory links periodically and update `data.js` when a fellowship changes its locator.

Current review date in the website: **August 12, 2026**.
