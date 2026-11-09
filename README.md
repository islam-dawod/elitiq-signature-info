# Elitiq Group — Email Signature (Info)
Elitiq Support · info@elitiq.com · Pill-strokes variant · 600 × 200 px

## Files
```
signature.html         relative image paths (reference)
signature-ready.html   absolute GitHub Pages image URLs — paste-ready for Outlook/Gmail
images/                logo-01, chip-light (ELITIQ SUPPORT), icon-01, deco-01
```

## Use in Outlook / Gmail
1. Open **signature-ready.html** in Chrome.
2. Select the signature, copy (Ctrl+C).
3. Paste into Outlook › Settings › Mail › Signatures (or Gmail › Settings › Signature).
4. Send a real test email to yourself and open it (not just the compose window) to confirm images load.

Email-safe: table layout, inline CSS only, no flex/grid/position, no JS, no base64.
All shapes (chip, decoration, icon, logo) are images, so they render the same in Outlook desktop.

## Notes
- The title chip is an **image** (`chip-light.png`) reading "ELITIQ SUPPORT", re-rendered in Urbanist
  to match the brand chip (mint → white → pink gradient, soft shadow).
- Name line and chip both read "Elitiq Support". To remove the chip or change its text, re-export the image.
- Keep total width at 600 px; don't scale images in CSS.
