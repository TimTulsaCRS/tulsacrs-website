# tulsacrs.com

Static marketing site for Content Recovery Specialists of Tulsa.
Deployed via FTP to Porkbun hosting (pixie-ss1-ftp.porkbun.com).
FTP deploy is handled by Tim's Hermes agent (ftp-website-deploy skill) after a PR merges — this repo does not auto-deploy.

## ⚠️ assets/ is an email-signature dependency — never delete/rename/modify

The files in `assets/` are loaded live by every CRS email signature from `https://tulsacrs.com/assets/`. Deleting, renaming, or modifying an existing asset breaks those signatures. Adding a new asset is okay, but changes to existing assets require Tim Odell's written approval.
