# OVERQUALIFIDE Labs archive

A historical skateboard-project website restored from the GitHub site and a fuller local website backup. Original writing, artwork, deck photography, and the June 16, 2010 press release are preserved.

## GitHub Pages

This is plain HTML and CSS. No JavaScript, dependencies, or build step is required. `.nojekyll` tells Pages to serve the files directly.

In **Settings → Pages**, choose **Deploy from a branch**, **master**, **/ (root)**.

Published address: https://rpvnwnkl.github.io/overqualifidelabs/

Preview locally with `python3 -m http.server 8000`, then open http://localhost:8000/.

## Restoration

- Preserves the red background, italic branding, original introduction, and original company/project copy.
- Restores About, Projects, Contact, Press, founder, poem, and manifesto pages from the local backup.
- Replaces the external gallery with the locally available artwork. Tumblr posts were not in the backup; the blog page explains the missing material without loading external scripts.
- Labels old contact details, sales copy, and guarantees as historical. Old commercial destinations are text, not current purchase links.
- Adds readable navy text, responsive layouts, semantic landmarks, skip navigation, visible focus, current-page navigation, meaningful titles, and image descriptions.
- Supplies HTML transcripts for the poem, manifesto, and press release while retaining original scans and the PDF.
- Records the Press page's 2020 date discrepancy; the PDF is dated June 16, 2010.
- Retains `home.html`, `hub.html`, and `/about/` as working historical entry points.
- Omits old server configuration, logs, editor previews, and Jekyll demo content from the public site. The supplied backup is untouched and original repository content remains in Git history.

## Verification

Check all internal links and images, keyboard navigation, small screens, and zoomed layouts before publishing. Navy `#000055` on red `#ff0000` has approximately 4.64:1 contrast. Original scans and the PDF have not been remediated; use the HTML transcripts for accessible reading. These changes are not a full accessibility certification.
