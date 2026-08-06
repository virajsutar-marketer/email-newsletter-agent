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

## Automation/sequence checklist

- [ ] Trigger event and goal state explicitly defined before writing any copy
- [ ] Each email in the sequence has one specific job — not generic "stay in touch" filler
- [ ] Spacing matches the real decision timeline of the trigger (fast for abandonment, slower for nurture) — not one universal cadence
- [ ] Explicit exit condition built in — sequence stops automatically once the reader completes the goal action
- [ ] Personalization/branching based on real behavior data where the platform supports it, not just a first-name merge tag
- [ ] Performance reviewed per-step, not only as one aggregate rate for the whole sequence

## Deliverability audit checklist

- [ ] SPF, DKIM, and DMARC verified correctly configured for the sending domain
- [ ] DMARC enforcement level checked against aggregate reports before tightening
- [ ] New/switched sending domains warmed up gradually — not sent at full volume immediately
- [ ] Hard bounces suppressed immediately; soft-bounce patterns tracked
- [ ] Unengaged subscribers re-engaged or suppressed on a recurring cadence
- [ ] No purchased, rented, or scraped list ever used
- [ ] Complaint rate monitored as its own metric, not inferred from open-rate decline alone
- [ ] Genuine, easy-to-find unsubscribe mechanism present in every commercial send
- [ ] Inbox placement checked across major providers, not just delivery/bounce status
- [ ] Authentication and reputation re-audited after any sending-infrastructure change (new ESP, new domain, list import, volume spike)
