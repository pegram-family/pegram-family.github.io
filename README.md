# The Pegram Family Album

An archive of the genealogy site that was published at pegram.family, preserved
as it was served.

`docs/` is a byte-for-byte snapshot taken on 2026-09-07: 4,725 files,
150,897,468 bytes, unmodified from the origin. `docs/index.html` is the site
root, and every path under `docs/` corresponds to a URL on the original site.

`.gitattributes` sets `* -text` so git never rewrites line endings. This is
frozen content — much of it hand-authored HTML from the late 1990s and 2000s,
and reformatting it would be a loss.

## Rights

See [LICENSE.md](LICENSE.md). This archive is not open-source licensed and no
reuse rights are granted — the material has many authors and the rights are not
mine to give. That file records what is known about provenance, reproduces the
site's own Statement of Policy, and explains how to raise an attribution or
removal request now that the original webmaster's address is defunct.

## About the original site

It was a static site behind Cloudflare, with `index.html` serving as the
directory index. Nothing ran server-side. The guestbook form, the visitor
statistics form, and the site search box all pointed at CGI scripts and
third-party services that stopped existing long ago, so those parts of the site
no longer function and have not functioned for many years.

## Where this is going

The site is published with GitHub Pages. `docs/` is the publish root because
Pages' deploy-from-a-branch mode can only serve the repository root or `/docs`,
and this keeps the served tree separate from the repository's own files.

`docs/.nojekyll` disables the Jekyll build so Pages publishes the tree verbatim.
Without it Jekyll drops `docs/wills/_vti_cnf` for its leading underscore and
burns build time templating four thousand static pages for no reason.

The pegram.family domain is being retired rather than pointed at Pages.

## Related

The site is also preserved in the Wayback Machine.
