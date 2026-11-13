# AI & Law — Book & Workshop Launch Site

## What is public
- `index.html`: public marketing homepage, workshop offers and future-book roadmap.
- `read.html`: **all nine sections of Chapter One**, extracted from `Aya(4)(1).docx` in order, including in-chapter tables and references.
- `interest.html`: interest form that **prepares an email enquiry**. No backend or database; no submission is falsely claimed.
- No unpublished chapter text or comparative supplement is included in this ZIP.

## Required before launch
1. Open `config.js` and replace the empty `AYA_CONTACT_EMAIL` string with your verified professional email. Until then, the form offers copy-only fallback; it cannot collect enquiries.
2. Open `interest.html` and submit a test; ensure your email app opens and you actually receive the message. Mailto relies on visitors having an email app and does not guarantee delivery.
3. For a real automated waitlist, connect a privacy-compliant external form provider and replace the mailto workflow; publish a suitable privacy notice and consent mechanism.
4. Review all legal and technical statements and source references before promoting the site as authoritative.

## GitHub Pages
Upload `index.html`, `read.html`, `interest.html`, `styles.css`, `config.js`, `.nojekyll` to the root of your repository. In **Settings > Pages**, publish from `main` and `/(root)`. Do not upload the original full manuscript or later chapters to the public repo.

## Updating
Send the updated manuscript; regenerate the reader content from the latest DOCX and keep the same page URLs. Avoid renaming existing chapter section IDs so existing links continue working.
