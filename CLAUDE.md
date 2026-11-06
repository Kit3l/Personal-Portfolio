# Hillary Kitel — Portfolio Project Brief

## About the Owner
- Name: Hillary Pchumba Kitel
- Role: Programmes & Communications Officer, DLCI (Drylands Learning & Capacity Building Initiative)
- Positioning: programmes-first (since 2026-08-09) and capability-first (since 2026-11-06, see Site Purpose below). Anchor title: "Programmes & Communications Professional". Supporting line: "Programme Delivery · Strategic Communications · Digital Systems".
- Sector: NGO / international development / pastoralist land rights & advocacy
- Location: Nairobi, Kenya
- Domain: kitel.site (hosted on GitHub Pages)
- Email: pchumbakitel@gmail.com
- Phone: +254 713 546 522
- LinkedIn: linkedin.com/in/kitel-hillary-19463020a
- Education: BSc Cooperative Business (Marketing Option), The Cooperative University of Kenya (undergraduate). Currently pursuing a Master's in Project Planning and Management (ongoing — institution not yet specified on site).
- Membership: Public Relations Society of Kenya (PRSK)

## Site Purpose: Capability-First (as of 2026-11-06)
The site no longer reads as job-seeking. It leads with capability and proof, and serves three audiences without any one undercutting the others:
- Employer: should see a focused, impressive range of skills.
- Potential project client: should see services they could commission.
- General visitor: should see a credible professional.

Tone rules:
- Lead everything with capability and proof, never with "freelance availability".
- Availability for independent projects is DISCREET: it appears in ONE understated place only, the footer contact block ("Whether you're building a team or commissioning a project, let's talk"). Never scatter it through the page, never a loud "hire me" cue.
- No pricing anywhere on the site. All pricing is conversation-led.
- Primary CTA wording is "Start a Conversation" (nav, About, footer heading). "Request CV" is secondary and lives only in the footer, as a quiet note under the contact links. The FAQ also links to it.
- Project captions describe what was delivered (outcome-focused), not the role held.
- Headings never end with a full stop.

## Real, Verified Metrics (use these — do not invent numbers)
- Social media growth: Twitter 300→1,400+, LinkedIn 400→2,500+, Facebook +1,000 followers — cumulative 600%+ growth over 3 years, 500,000+ total platform impressions
- Pastoralist Leadership Summit: 100,000+ digital interactions
- 3 DLCI projects closed, improving lives of 100,000+ beneficiaries
- 20 reports published, 10 policy/discussion briefs edited
- ~10,000 photo assets, ~20 video productions
- MEAL system: designed & in development (PostgreSQL, Node.js, Railway, KoboToolbox)

## Site Structure
- index.html — main portfolio (self-contained, all CSS inline). Section order: Hero → Stats → About → Capabilities ("What I Do", 4 cards: Programme Delivery & MEAL, Strategic Communications, Web & Digital Builds, Systems & Administration, each with an "In practice" proof point) → Featured Projects → Testimonials → Footer (FAQ + contact).
- media.html — videos (4 YouTube) + photo albums (3 Google Drive albums)
- reports.html — currently deactivated in nav (no reports shared yet)

## Projects
- Community Land Dashboard (live): https://kit3l.github.io/Community-Land-Dashboard/index.html
- MEAL Dashboard (live): https://meal-system-production.up.railway.app/landing.html
- Pastoralist Leadership Summit Website (live): https://dlci-hoa.org/pastoralist-leadership/pls/
- Skipp Carrier: no public link. The card shows "Walkthrough on Request →" (goes to the contact section).

## DESIGN DIRECTION: Muted Green Editorial
Calm, warm, sophisticated — the visual language of a premium wellness or editorial brand. Superseded the earlier "Editorial Noir" (dark/gold) direction; no pure black, no harsh full-bleed dark imagery, no heavy feel anywhere on the site.

- Palette: deep muted olive/sage green (~#444b38) for feature sections and the hero; warm cream/bone (~#f4f1e8) for alternating sections; deep charcoal (~#2a2a24) as text on cream; warm cream as text on green; soft muted gold/sand (~#c9a86a) as the ONE accent, used sparingly (logo, links, hover states, section-label hairlines) — never as a structural/background colour.
- Typography: Playfair Display headlines, elegant and confident, generous letter-spacing, small-caps treatment for the hero and section titles, centered. Body copy stays quiet and clean (Poppins). Thin hairline dividers between subsections, not heavy borders.
- Layout: alternate deep-green and cream section panels down the page so it breathes — never two dark sections in a row, never all-dark. Capabilities sits on the warmer bone tone (--cream-deep, #ece6d6) between green About and cream Projects. No borders between sections — the colour change itself is the divider. Centered, restrained, generous whitespace.
- Links & buttons: simple understated text links ("Learn more" style, thin underline or hairline border), not heavy filled buttons. Where a real button is needed (form submit), keep it a thin outline that fills on hover — never a solid heavy block.
- Photography: profile photo stays softly framed with rounded corners and a thin sand hairline border — not aggressive full-bleed.
- Keep the UnifrakturCook HK monogram logo, now in sand/gold, set against the green nav bar.
- Motion: subtle only, unchanged from before — gentle staggered fade-up on scroll, slow hover eases, nothing bounces or spins.

## Requirements
- SEO: full meta tags, Open Graph, Twitter cards, canonical URL, semantic HTML, one H1 per page, alt text on all images, descriptive link text. Meta description (since 2026-11-06) frames programme delivery, strategic communications, and digital systems for mission-driven organisations. Target keywords: "Programme Officer Kenya", "Project Management NGO", "Development sector Nairobi", "Strategic Communications".
- AI/AEO optimization: JSON-LD structured data (Person schema with name, role, employer, location, sameAs links); clear entity definition; consider an FAQ section.
- Add sitemap.xml and robots.txt.
- Contact form stays mailto-based (no backend). The footer's "Request CV" link (secondary, footer only) pre-fills the form.
- Phone number revealed on click, not displayed publicly.

## Working Style
- We redesign step by step, one section at a time, starting with index.html.
- Show me each change before moving on.
- Preserve all real content and metrics; only change design/structure.
