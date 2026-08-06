# Quick-Reference Checklists

Condensed checklists distilled from [`EMAIL-NEWSLETTER-PLAYBOOK.md`](./EMAIL-NEWSLETTER-PLAYBOOK.md). Use these for fast gates; use the playbook for the reasoning behind each rule.

---

## Pre-send checklist (every email)

- [ ] Copy reads as human — punchy, specific, no corporate hedge-speak or AI-tell openers
- [ ] No banned filler phrases or empty superlatives ("revolutionary," "cutting-edge," "game-changing")
- [ ] Signed by a real name/voice, not "The Team"
- [ ] Launch/announcement emails lead with a real, verified stat — not the product name
- [ ] Any urgency/scarcity claim is real — no fabricated countdowns, no invented slot counts or deadlines
- [ ] CTA uses possessive/claiming language ("Claim my...") over passive ("Get my...", "Learn more")
- [ ] Hero shows the actual product/outcome doing something real — not generic decorative art
- [ ] Any example number in the hero explicitly labeled as an example
- [ ] One flow, one CTA — hook → proof → image → CTA, not multiple stitched-together topics
- [ ] Only one full-weight offer per send; secondary items demoted to a small text-only strip
- [ ] Content matches the segment it's going to (prospect / customer / advocate framing correct)
- [ ] Any customer quote/testimonial/stat used only with explicit sign-off for this specific send

## Technical build checklist (MJML / email-safe HTML)

- [ ] Compiled with strict validation, zero errors
- [ ] Grepped for inline SVG/vector tags — zero matches
- [ ] Grepped for leftover unswapped placeholder tokens — zero matches
- [ ] All images hosted at a public, permanent URL — no data-URI/base64 images
- [ ] File size under the clipping threshold for major webmail clients
- [ ] Rendered and visually verified at true in-email width and mobile single-column width
- [ ] Merge-tag/personalization syntax intact, no stray broken markup
- [ ] Most important number duplicated as real selectable HTML text, not only inside the hero image
- [ ] Text contrast checked on light backgrounds (no illegible light-gray body text)
- [ ] Final "read it cold" pass done as a skeptical recipient before shipping
