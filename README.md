# BridgeScale Advisors — Website (Contractor Pipeline)

## Deploy to GitHub Pages
1. Copy ALL files in this folder into the root of the GitHub Pages repo (replacing existing files).
2. Commit and push. GitHub Pages redeploys automatically (1–2 min).
3. Hard-refresh (Cmd/Ctrl+Shift+R) — the Pages CDN caches for 2–10 min.

## IMPORTANT — deployment safety
- The repo contains a **CNAME** file (bridgescaleadvisors.com). DO NOT delete it when replacing files. Upload these files alongside it.
- Always deploy the COMPLETE set of files. Partial uploads cause version mismatches between pages.

## Canon alignment (July 2026)
Aligned to the "Execution for BridgeScale" Drive folder — AI_HANDOFF_BRIDGESCALE.md and Bridgescale_Website_Funnel_Build_SOP_v1.docx.

- **Voice:** first-person Joshua (handoff non-negotiable #4). Not firm-voice "we". Entity-level legal disclaimers remain third-person ("BridgeScale is not a lender") — that is a factual statement about the company, not narration.
- **Palette:** navy `#0f1e35` · deep `#08111f` · gold `#c9a84c` · gold-light `#e8c97a` · cream `#f0ece2`. Matches bridgescale_scorecard_v6.html.
- **Framework:** four invisible ceilings (personal credit → business credit → working capital → bond capacity), expressed publicly as the five doors from BridgeScale_VSL_Script.
- **Location:** United States (nationwide).

## Files (18)
- index.html / espanol.html — homepages
- about.html / about-es.html — founder + partner bios
- pricing.html / pricing-es.html — full price menu
- contact.html / contact-es.html — assessment booking
- stage-1-personal-credit … stage-4-contract-ready (EN) + stage-1-es … stage-4-es (ES)
- styles.css — all styling
- README.md — this file

## Open items
- **Josh's bio** — about.html and about-es.html ship with [PLACEHOLDER] blocks for his bio, title, and headshot. Drop-in when received; updates both files.
- **Scorecard** — bridgescale_scorecard_v6.html (Drive: Execution folder) is production-ready and needs two strings: YOUR_GHL_WEBHOOK_URL and YOUR_GHL_CALENDAR_URL. Blocked on GHL account.
- **Footer disclaimer** — review with counsel alongside the service agreement.

## Known divergences from the Website SOP (raise with Josh)
- SOP specifies **Framer** as the platform; this is hand-built static HTML on GitHub Pages.
- SOP Decision B places the **Spanish site in Phase 4** (post-week-8); it shipped in week 1.
- SOP homepage spec is nine fixed sections with a three-path selector; this site uses a five-door locator.

Neither divergence blocks anything today, but both are live and worth a decision.
