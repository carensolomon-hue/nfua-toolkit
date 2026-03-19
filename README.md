# NRI Advocacy Toolkit — Neighbors for a United Atlanta

Live site: **https://carensolomon-hue.github.io/nfua-toolkit**

This is the grassroots advocacy toolkit for [neighborsforaunitedatlanta.org](https://neighborsforaunitedatlanta.org). It provides plain-language explainers, downloadable resources, and ready-to-use social media posts for every topic related to the Neighborhood Reinvestment Initiative (NRI) and Tax Allocation Districts (TADs).

## How to Add or Update Content

### Adding a new PDF or image to a topic page
1. Upload the file to the `downloads/` folder in this repository
2. Update the relevant topic page in `topics/` to link to the new file

### Updating social media posts
Open the relevant topic HTML file in `topics/` and edit the post text directly in the `<div class="post-text">` blocks.

### Adding a new topic page
1. Copy an existing topic file from `topics/`
2. Update the content
3. Add a new card to `index.html` pointing to the new page

## File Structure

```
index.html          — Toolkit hub with search and filters
shared.css          — Shared styles for all pages
topics/
  food-access.html  — Fully built (explainer + downloads + social posts)
  housing.html      — Explainer built, social posts coming
  healthcare.html   — Coming soon
  education.html    — Coming soon
  greenspace.html   — Coming soon
  homelessness.html — Coming soon
  economic.html     — Coming soon
  antidisplacement.html — Coming soon
  tad101.html       — Coming soon
  financials.html   — Coming soon
  tad-did-that.html — Coming soon
  tad-by-tad.html   — Coming soon
downloads/
  financials-onepager.pdf — The Financial Case one-pager
```
