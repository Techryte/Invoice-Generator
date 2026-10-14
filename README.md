# Export Invoice Builder

A free, browser-only invoice generator for Indian freelancers and consultants who bill clients abroad.

**Live:** https://techryte.github.io/Invoice-Generator/

## What it does

- Live A4 preview as you fill in your details, client, service lines and bank details
- Zero-rated export of services wording: IGST @ 0%, with the LUT declaration when you enter a GSTIN, or the unregistered-supplier wording when you don't
- SAC codes per line (998314 development, 998313 IT consulting, 998315 hosting)
- Totals, due date from payment terms, and the amount in words
- Client company ID type and country are editable (ACN, ABN, VAT No., EIN…)
- **Download PDF** or **Print** (choose "Save as PDF" in the print dialog)
- **Next invoice** increments the number (e.g. `2026-27/001` → `2026-27/002`) and resets hours

## Privacy

There is no server. Everything you type is saved only in your own browser's local storage, so it is there next time you open the page on the same device. **Clear saved data** removes it.

## Run locally

Open `index.html` in a browser. No build step.

## Files

- `index.html` — the whole app (HTML, CSS, JS)
- `vendor/` — [html2canvas](https://github.com/niklasvh/html2canvas) 1.4.1 and [jsPDF](https://github.com/parallax/jsPDF) 2.5.1 (MIT), used for the PDF export

## Disclaimer

This is a template, not tax advice. Confirm your GST registration, LUT and income-tax position with a chartered accountant.
