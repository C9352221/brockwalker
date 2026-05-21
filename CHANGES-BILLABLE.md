# Brock Walker Personal Site — Billable Changes Log

**Site:** brockwalker.com
**Client:** Brock Walker
**Free round used:** Revision Round 1 (commit `f17a587` — 2026-05-XX)
**Status:** Site held pre-launch. All changes below are post-free-round and billable to Brock.

---

## How this log works

Every change Brock requests AFTER the free revision round is logged here with:
- Date requested
- Short description of the change
- Files touched
- Commit ref (once committed)
- Status (requested / done / live)

Marc will send Brock a summary invoice from this log before pushing the site live.

---

## Pricing note

Per Brock's package: Starter ($515) included 1 revision round. Additional rounds are à la carte. Rate TBD by Marc — typical small change bundles bill per round, not per micro-edit.

---

## Changes

### Round 2 — 2026-05-21 (post-free-round, billable)

| # | Date | Change | Files | Commit | Status |
|---|------|--------|-------|--------|--------|
| 1 | 2026-05-21 | Removed "About Me" eyebrow label above the Brock Walker title | `index.html` | `c9bf5a6` | done |
| 2 | 2026-05-21 | Replaced 3 long bio paragraphs with shortened version (Sandusky → Florida → Wells Fargo → 2007 mortgage co. → 20+yr MLO + Christian travel agency + married Rafina 2026) | `index.html` | `c9bf5a6` | done |
| 3 | 2026-05-21 | Swapped hero photo from solo `brock-travel-agent.jpg` to new Brock + Rafina hot-air-balloon photo (resized 2735×3260 → 900×1073, optimized 1.5MB → 182 KB, saved as `brock-rafina-balloon.jpg`) | `index.html`, `assets/brock-rafina-balloon.jpg` (new) | `c9bf5a6` | done |
| 4 | 2026-05-21 | Shortened pullquote from *"What drives me every day is the desire to do God's will."* to *"I aim to do God's will & be my best."* | `index.html` | `c9bf5a6` | done |
| 5 | 2026-05-21 | Removed "Where Faith Meets Work" h2 subtitle under What I Do section (kept "What I Do" eyebrow as the heading) | `index.html` | `c9bf5a6` | done |
| 6 | 2026-05-21 | Added two-column compliance disclosures in black footer — left: Core Financial, Inc. NMLS #252580 / Brock Walker / Mortgage Loan Originator NMLS #337948 — right: Star Walker Ministries LLC / Fla Seller of Travel Ref. No. ST44868. New CSS for `.footer-compliance` (desktop side-by-side, mobile stacked) | `index.html`, `css/style.css` | `c9bf5a6` | done |
| 7 | 2026-05-21 | Changed bottom CTA buttons from all-caps "MORTGAGES" / "HOLY SPIRIT LED TOURS" to title case "Mortgages" / "Holy Spirit Led Trips". New `.btn-title` CSS class overrides uppercase + tightens letter-spacing | `index.html`, `css/style.css` | `c9bf5a6` | done |

---

### Round 3 — 2026-05-21 (post-free-round, billable)

| # | Date | Change | Files | Commit | Status |
|---|------|--------|-------|--------|--------|
| 8 | 2026-05-21 | Removed `NMLS # 33794` reference from the top body paragraph (compliance number now lives only in the footer disclosure). Brock confirmed the correct number is `337948` and elected to keep the body clean | `index.html` | `cbe18bc` | done |
| 9 | 2026-05-21 | Rewrote the "Something Else You May Find Interesting" section to include baseball alongside MMA. New copy: *"I have had a couple of amateur MMA fights & played baseball through college. Learning to face my fears & be disciplined has helped me commit to trying to be my best personally, professionally, spiritually & in all areas of life."* | `index.html` | `cbe18bc` | done |
| 10 | 2026-05-21 | Changed bottom red CTA button from "Holy Spirit Led Trips" to "Holy Spirit Led Tours" | `index.html` | `cbe18bc` | done |
| 11 | 2026-05-21 | Footer restructured from 2-column compliance row to a full 3-column layout. New center column contains: Brock Walker (name), 813-956-0537 (clickable `tel:`), BrockWalker@BrockWalker.com (clickable `mailto:`), and the "Do What Is Best For People" tagline | `index.html`, `css/style.css` | `cbe18bc` | done |
| 12 | 2026-05-21 | Added `www.TheMortgageMaster.com` as a clickable link beneath the Mortgage Loan Originator compliance line in the footer left column | `index.html` | `cbe18bc` | done |
| 13 | 2026-05-21 | Added `www.HolySpiritLedTours.com` as a clickable link beneath the Fla Seller of Travel compliance line in the footer right column | `index.html` | `cbe18bc` | done |

---

## Decisions on file

- **NMLS numbers — Round 2 vs Round 3:** Round 2 used Brock's wording verbatim (`NMLS # 33794` in body, `#337948` in footer). Round 3 (this round) removed the body reference entirely at Brock's request. Footer disclosure remains `#337948`.
- **"What I Do" section heading:** kept as just the "What I Do" eyebrow per Brock's literal request; no larger h2 added back in.

## Open items still on the wish list

- **Old hero photo `brock-travel-agent.jpg` is still in `/assets`.** It's no longer referenced in the live HTML, but it IS still the social-share Open Graph image (`<meta property="og:image">`). Facebook/iMessage previews will continue to show the solo travel-agent photo until/unless we point OG at the new Brock+Rafina photo. Ask if you want this updated.

---

## Notes / Context per change

<!-- Add longer-form context here per change as needed -->
