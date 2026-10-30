# Mintfluences website

A static, responsive website for Mintfluences. Open this folder in VS Code and edit `index.html`.

## Preview locally

Open `index.html` in a browser, or use VS Code's Live Server extension.

## Contact form

The consultation form opens the visitor's email app and prepares an inquiry to `hello@mintfluences.com`.

## Hosting

This site is published with GitHub Pages from the `main` branch root. The repository is public because GitHub Pages is available for public repositories on GitHub Free.

## Custom domain setup

The repository's custom domain is `mintfluences.com` (also stored in `CNAME`). In IONOS, configure the apex DNS with GitHub Pages' four IPv4 A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Optionally add GitHub Pages' four IPv6 AAAA records. For `www.mintfluences.com`, add a CNAME to `jenk410.github.io`. Keep existing email-forwarding MX/TXT records. After DNS resolves, enable Enforce HTTPS in the repository's Pages settings.

