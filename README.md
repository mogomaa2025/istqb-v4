# ISTQB Foundation Level v4 – Chapter Summaries

A simple, static website containing concise summaries for ISTQB Foundation Level v4 chapters. Open `index.html` in your browser to navigate to each chapter.

## Test
https://shorturl.at/4bqV9

## Mointor Clicks
https://www.shorturl.at/url-total-clicks.php?u=shorturl.at/4bqV9

## Overview
- Pure HTML files, no build tools or dependencies required
- Works fully offline
- Organized by chapter directories (e.g., `ch1`, `ch2`, …)
- Some chapters include multiple summary variants (e.g., `chapter1-summary.html` and `chapter1-summary2.html`)

## Project Structure
- `index.html` – Landing page linking to chapters
- `ch1/` … `ch6/` – Per-chapter folders containing summary pages
  - Example files (based on current contents):
    - `ch1/chapter1-summary.html`
    - `ch1/chapter1-summary2.html`
    - `ch2/chapter2-summary.html`
    - `ch2/chapter2-summary2.html`
    - `ch3/chapter3-summary2.html`
    - `ch4/chapter4-summary.html`
    - `ch5/chapter5-summary.html`
    - `ch6/chapter6-summary.html`

Note: Actual files may evolve; add or remove pages as needed.

## How to Use
- Double‑click `index.html` to open in your default browser
- Or right‑click `index.html` → “Open with” → choose your browser

Optional: Serve locally for cleaner relative URLs
- Python 3: `python -m http.server 8000`
- Then open: http://localhost:8000/

## Editing and Extending
- To edit a summary: open the corresponding `chapterX-summary*.html` file in your editor, make changes, and refresh the browser
- To add a new chapter:
  1. Create a folder `chN` (e.g., `ch7`)
  2. Add a file `chapterN-summary.html`
  3. Update `index.html` navigation to link to `chN/chapterN-summary.html`
- To add an alternate version of a chapter summary: create `chapterN-summary2.html` (or similar) alongside the original

Conventions and tips
- Keep headings and section order consistent across chapters for easier scanning
- Use relative links so pages work offline (e.g., `../index.html` for “Back to Home”)
- Keep HTML simple and readable—no frameworks are required

## Version Control
This folder appears to be a Git repository. Typical workflow:
- View changes: `git status`
- Stage and commit: `git add -A && git commit -m "Update summaries"`
- Create branches for larger changes: `git checkout -b feature/your-change`

## Troubleshooting
- If links don’t work, verify relative paths (e.g., `href="../index.html"` from chapter pages back to the root)
- If a chapter doesn’t appear on the home page, ensure you added the link in `index.html`

## License
No license specified. Add a LICENSE file to clarify usage if you plan to share or publish.

## Download
https://shorturl.at/egbGW

## Monitor Download Clicks
https://www.shorturl.at/url-total-clicks.php?u=shorturl.at/egbGW
