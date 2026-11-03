# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Stack

Static HTML/CSS mockup in `site/`, deployed to GitHub Pages on every push to `main` (`.github/workflows/pages.yml`), for pastor and staff review. The real site will be built on Payload CMS + Next.js; the mockup does not need to use them.

## Users

- Members, cell group leaders, and branch staff who come to watch live services, morning prayer, and sermons.
- Newcomers learning about the church and preparing a first visit. They get information only: no visit booking, since newcomers fill in their details on site at the church.
- Reviewers of this mockup: pastors and staff.
- Mobile first; elderly members must be supported (contrast, tap target size).

## Product Purpose

Website revamp for 611 靈糧堂 (Bread of Life Christian Church, Tsuen Wan main campus). The revamp simplifies the menu and homepage so people reach what they came for quickly: live streams, morning prayer reading, sermons, and first-visit information. Success is a visitor reaching that content without hunting through the menu. Source brief: `ref/homepage-brief.md` (v6, 2026-11-03, on branch `docs/homepage-brief`).

## Positioning

The live-stream "channel picker" (choose a service or series like choosing a TV channel, with live indicator, countdown, and schedule) is the existing site's strength and is kept. Morning prayer reading with a 14-day plan lives on the homepage only, not in the menu.

## Operating Context

- Languages: Traditional Chinese primary; core pages in Chinese, English, and Japanese. Pages with no Japanese version are hidden in the Japanese interface. Japanese serves the Japan branch.
- Morning prayer replays by language: Cantonese/Mandarin (audio plus YouTube), English, Tagalog, Bahasa Indonesia, Español. Live prayer runs in Cantonese and Mandarin at the same time.
- Reference material in `ref/`: competitor analysis of chc.org.sg (intent-based IA), elevationchurch.org analysis (2-slide hero, "next step" module on sermon pages), kingdomcity.com, and earlier 611 sitemap drafts (20261029, 20261030).
- `site/index.html` is currently a sitemap/IA diagram, not yet a page design.

## Capabilities and Constraints

- Menu (7 items): Watch, Locations, Join, Equip, News, Give, About. Toolbar: search, language switch, staff portal. Equip and News submenus are undecided.
- Locations lists only the Tsuen Wan main campus (one page with interactive map, transport, parking); branch locations live under About.
- Join pages each end with an application form button.
- Homepage order: hero carousel (2 slides), live channel picker, morning prayer + Sunday sermons, announcements + event carousel, pastoral areas, equip, footer.
- Hero slide 1: welcome video, muted and looping on desktop, static poster on mobile, data-saver, and reduced-motion. Slide 2: latest service with live and not-live states.
- Fonts suggested: Noto Sans TC (body), Noto Serif TC (headings).
- Section names describe what the visitor wants to do, not the org chart.
- Content model will eventually live in Payload CMS, so mockups should map to editable collections and fields.
- Open: pre-stream countdown on hero slide 2; Equip/News dropdowns; pastoral area order; who updates the event carousel and how often; whether channel countdowns show only when starting soon; giving provider; livestream/sermon sources.

## Brand Commitments

- Names: 611 靈糧堂 / Bread of Life Christian Church, used as written.
- Logo palette is binding: Pantone 129C yellow, 158C orange, 370C green, plus olive-gold (50C 50M 100Y) for the wordmark. Reference: `ref/611 logo color code.jpeg`.
- Visual direction: the conventional church-site standard, executed plainly and at full craft, with Elevation Church (elevationchurch.org) and Kingdom City (kingdomcity.com) as the quality bar. No novelty visual world.
- The brush-script "611" mark and its three lockups (stacked, two-line horizontal, one-line horizontal) stay unaltered. Source: `logo/611 logo+pantone color update2026ai.ai`.

## Evidence on Hand

- Logo source file and color-code image (above).
- `ref/homepage-brief.md` and the competitor and reference analyses in `ref/`.
- The welcome video and poster images are to be supplied by the church and do not exist yet. No real photography, testimonials, service data, or copy supplied; do not fabricate them.

## Product Principles

1. Organize by what the visitor wants to do, not by ministry or department.
2. Live streams and morning prayer are never pushed below the fold by the hero.
3. Newcomers get information, not a booking funnel; first-visit info is one step from the homepage.
4. Chinese leads; titles follow the chosen language, never bilingual pairs.
5. Everything mocked must be editable by non-developers through the CMS.

## Accessibility & Inclusion

Mobile-first with high contrast and large tap targets for elderly members. Autoplay video respects reduced-motion and data-saver; carousels pause on hover and keyboard focus and have manual controls.
