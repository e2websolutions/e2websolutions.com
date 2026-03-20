# Demo → Client Handoff Checklist
## Roofing Demo (and future contractor demos)

When a contractor picks a demo site as their template, work through these in order.

---

### 1. Business Identity
- [ ] Business name — replace all instances of "Your Roofing Company"
- [ ] Tagline/slogan (if they have one) — update hero badge and footer tagline
- [ ] Years in business — update "15+ Years Excellence" callout
- [ ] Service area — update "North Carolina" / city references throughout

### 2. Contact Info
- [ ] Phone number — replace `(828) 555-1234` everywhere (nav CTA, hero CTA, footer)
- [ ] Email — replace `info@yourroofingcompany.com`
- [ ] Address — replace `1234 Contractor Way, Charlotte, NC 28202`

### 3. Services
- [ ] Confirm which of the 4 services they actually offer (Roof Replacement, Siding, Gutters, Home Repairs)
- [ ] Remove or rename service cards for anything they don't do
- [ ] Update service descriptions to match their specific offerings/materials (e.g. GAF certified — do they actually have this?)

### 4. Content & Copy
- [ ] Hero headline — personalize to their city/region
- [ ] Hero subheadline — update "protect your home" copy to match their voice
- [ ] Testimonials — replace placeholder names (Maddie Pisarsky, Trish Roscoe, Daniel Scott) and quotes with real reviews
- [ ] Testimonial locations — update city names to match their actual service area
- [ ] "Why Choose Us" bullets — verify Licensed & Certified, GAF claims are accurate for this contractor

### 5. Images
- [ ] Hero background — replace AI placeholder with real job photo
- [ ] "Why Choose Us" section image — replace with real contractor/crew photo
- [ ] CTA banner background — replace with real project photo
- [ ] Testimonial avatars — initials are fine, or swap for real headshots if provided

### 6. Social Media
- [ ] Footer Facebook link — replace `#` with actual URL
- [ ] Footer Instagram link — replace `#` with actual URL
- [ ] Footer LinkedIn link — replace `#` or remove if not used

### 7. Lead Form
- [ ] Connect form to a real handler — options:
  - Formspree (free tier, no backend needed): add `action="https://formspree.io/f/XXXXX"` to `<form>`
  - Netlify Forms: add `netlify` attribute to `<form>` (free, built-in if hosted on Netlify)
- [ ] Update "Select Service Needed" dropdown options to match their actual services
- [ ] Confirm form email recipient

### 8. SEO & Meta
- [ ] `<title>` tag — replace with actual business name + location
- [ ] `<meta name="description">` — write 1-sentence description with city/service keywords
- [ ] Copyright name in footer

### 9. Domain & Hosting
- [ ] Set up custom domain (purchased by client or by E2)
- [ ] Connect domain to Netlify site
- [ ] Verify SSL is active post-deploy

### 10. Final QA
- [ ] View on mobile — check nav, form, hero layout
- [ ] Click all CTAs — confirm phone/email links work
- [ ] Submit test form — confirm lead arrives at client's email
- [ ] Check all social links point to real pages

---

**Time estimate:** ~2–3 hours with client-provided content. Longer if sourcing photos or writing copy from scratch.
