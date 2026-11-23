# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Astro (static site generation) + Tailwind CSS. Chosen by the user over a Next.js option: a static marketing/vitrine site has no need for an app runtime, and Astro ships the least JS for a mobile-first, content-driven brochure site.

## Users

Primary users are local residents in and around Sainte-Catherine-de-Fierbois (37) browsing on mobile, looking for: wellness/relaxation activities (yoga, stress management), hands-on cooking workshops, or a bookable room near them. A secondary audience is small businesses/practitioners looking to rent a room (Salle 1 / Salle 2) for their own sessions. A third, newer audience is neighbors interested in buying local-producer goods (eggs, honey, vegetables) via a self-service locker system on site.

## Product Purpose

"Les Ateliers du 9" is a real physical venue (9 rue de la Godefroy, 37800 Sainte-Catherine-de-Fierbois) run by two independent practitioners sharing the space: Stéphanie Ollivier ("Chez Steph" — cooking workshops, Guy Demarle/Kobold product demos, becoming a home sales rep, stress/emotion management) and Vincent Machet ("Aromethyl" — ex-military stress-management coach, laughter yoga, individual wellness coaching). The site's job is to get a visitor to understand what happens there, pick the right practitioner/activity, and act: book a workshop/event, rent a room, or (new) grab local-producer goods from a locker. Success is a booking/call/email initiated from the site, not pageviews.

## Positioning

Not a wellness studio franchise or an anonymous co-working space — a single welcoming house run by two named, reachable people the visitor can picture meeting, each with a distinct specialty (culinary/home-sales vs. stress-coaching/yoga), sharing one warm physical place. The new lockers extend that same "real people, real place, drop by" logic to local food rather than positioning the site as an e-commerce storefront.

## Operating Context

- Single physical location, two practitioners operating semi-independently under one shared roof and one shared site.
- Events are small-group and in-person (4–10 people), booked by phone/SMS/email or via HelloAsso.
- Two rentable rooms on site (60m² multi-use room; 20m² coaching/wellness room), rented out to third parties.
- New: a physical locker wall on site where customers who buy online unlock a specific numbered locker in person to collect local-producer goods (eggs, honey, vegetables, etc.).

## Capabilities and Constraints

- No e-commerce/booking backend exists today; all booking currently happens via phone/email/HelloAsso links, not in-app. The rebuild stays a static informational site that routes to those same real-world booking channels — it does not add checkout.
- Mobile is the dominant device: the audience is a small local community, mostly phone browsing, not desktop research.
- The lockers feature is brand-new and has no real pricing/stock data yet. Its page uses explicitly fictional placeholder product/pricing content provided by the user, clearly swappable later — future work must not treat that content as real evidence.
- Room-rental pricing is real (grille « Tarifs location de locaux 2026 », Aromethyl / Vincent Machet), shown in full on the page. Rental contact = Vincent.

## Brand Commitments

- Name: "Les Ateliers du 9". Existing wordmark logo (green-on-beige + white/green reverse variants + sticker variants) supplied by the client in a "Kit de com" PDF — binding, not to be redrawn.
- Palette (binding, from client kit): `#1F4A33` fir green (primary — logo, titles, strong fills), `#EDE6D2` beige (primary background/paper), `#FFFFFF` white (text on green), `#141414` near-black (body copy), `#CFC7B6` taupe (details/hairlines).
- Typography (binding, from client kit): **Londrina Solid** for headings/display (matches the logo's poster-ish character), **DM Sans** for body copy.
- The client explicitly wants the new visual identity (sharper fir-green/beige system) to replace the site's current softer, bohemian-zen look, even though real on-site photography (patterned tiles, antique wood furniture, candles, yoga mats, "Vivre l'instant présent" signage) stays in that older cosy register and will need recropping/treatment to sit inside the new system rather than fight it.

## Evidence on Hand

- Current live site content fully captured (all 6 pages: home, Chez Steph, Aromethyl, Événements, Location de salles, Contact) — real copy, real contact details, real address, real event pricing (30€ journée, 25€ soirée), real social handles.
- ~16 real on-site photos at `/Users/stanislasbeaudoin/Library/Mobile Documents/com~apple~CloudDocs/Site - les ateliers du neuf/` (unprocessed phone photos, bohemian-zen interior, yoga mat, a practitioner mid-session).
- Brand kit PDF at `/Users/stanislasbeaudoin/Downloads/KIT DE COM - AD9.pdf` (logo files as flattened PDF graphics, not vector exports — logo will need to be re-extracted/vectorized or cropped from the PDF for production use).
- Absent: no real product/pricing data for Casiers locaux; the fictional locker list was removed (15/11/2026), add real producers when they exist.
- Split rule (15/11/2026, from Stéphanie): Chez Steph = cuisine only (Guy Demarle, Kobold, devenir conseillère); Aromethyl = bien-être only (stress, yoga, yoga du rire, séminaires). Never mix the two.

## Product Principles

1. Real people over generic wellness-brand voice — always name Stéphanie and Vincent, keep their own words/offerings distinct rather than merging into one faceless "team".
2. Mobile-first simplicity, especially on the new Casiers locaux page — short, scannable, no interactive map or heavy widget.
3. The new fir-green/beige identity fully replaces the old cosy-bohemian look site-wide; existing photos are source material to be re-treated, not a visual anchor to preserve.
4. Never present placeholder pricing/stock (rooms, lockers) as confirmed fact — keep it visually and tonally swappable.
5. Drive every page toward one of the three real-world actions the business can actually fulfill today: book an event/workshop, inquire about a room, or (new) buy into a locker — not toward pageviews or generic engagement.
