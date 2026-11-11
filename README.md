# Jibidy OS website (public, static)

This repository is for the public marketing/legal website only. Never add private JOS Core source, API keys, cookies, customer files, internal receipts or operational evidence.

## Deploy

1. Repository: `JibidyOS/jibidyos-site` (public).
2. Upload the contents of this directory to the repository root.
3. GitHub Settings → Pages: deploy from branch `main`, folder `/(root)`.
4. GitHub Pages custom domain: `jibidyos.com`. Configure the custom domain in GitHub **before** modifying DNS at the registrar.
5. At the domain registrar: remove the old Base44 apex A and www CNAME, then add the four GitHub Pages apex A addresses and www CNAME to `jibidyos.github.io`. Do not delete NS, MX, TXT or any email/DNSSEC entries.
6. Verify HTTPS on `/`, `/legal/`, `/privacy/`, `/terms/` and www redirect. Enforce HTTPS in GitHub when available.

This site contains the operator's public postal address in legal and privacy pages as explicitly authorized by the operator. Publishing a public repository makes it part of Git history.

No build system, external JavaScript, paid hosting or server is required.