# Certifications

One **sub-folder per certification**, each wired to a card in the `// 07 Certifications`
section of `portfolio.html`.

```
assets/certifications/
└─ intro-to-cybersecurity/   Cisco Networking Academy — Introduction to Cybersecurity
   ├─ certificate.pdf        the certificate itself (linked by the "View certificate" button)
   └─ cover.png              preview image shown at the top of the card
```

## Adding a new certification

1. Create `assets/certifications/<slug>/`.
2. Drop the certificate in as `certificate.pdf`.
3. Add a preview image as `cover.png` (or `.jpg` / `.jpeg` / `.webp`) — this is what shows
   on the card; clicking it opens the fullscreen lightbox. If the certificate is a PDF,
   a screenshot of the first page works fine (~1400px wide).
4. Tell me the issuer + what the course covered, and I'll add the card
   (`<div class="cert-card" data-assets="assets/certifications/<slug>">`) with the
   English and French text.

Extra photos can go in as `gallery-1.*` … `gallery-6.*` — see `assets/README.md` for the
full naming convention. Any file you leave out is simply hidden.
