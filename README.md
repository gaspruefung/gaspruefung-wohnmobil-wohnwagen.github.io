# Mobile Gasprüfung – Wohnmobile & Wohnwägen

Static one-page website for a mobile gas inspection service (DVGW G607) for
motorhomes and caravans in the Stuttgart area. Built as a plain HTML/CSS site
for GitHub Pages — no build step required.

## Files

| File               | Purpose                                              |
| ------------------ | ---------------------------------------------------- |
| `index.html`       | Landing page (services, benefits, process, contact)  |
| `impressum.html`   | Legal notice (§ 5 DDG) — legally required in Germany |
| `datenschutz.html` | Privacy policy (GDPR / DSGVO) — legally required     |
| `style.css`        | Shared styles for all pages (responsive)             |
| `xxx-kleiner.jpg`  | Header image                                         |

## Still to fill in (placeholders)

Search the HTML for `BITTE` comments. Currently optional:

- **Impressum** – DVGW certificate number / issuing body, if available.

## Local preview

Open `index.html` directly in a browser, or serve the folder:

```sh
python3 -m http.server 8000   # then open http://localhost:8000
```
