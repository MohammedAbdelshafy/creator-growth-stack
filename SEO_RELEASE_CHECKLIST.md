# Creator Growth Stack — SEO release checklist

## URLs and scope
- Main site: https://mohammedabdelshafy.github.io/creator-growth-stack/
- Proposed service landing page: https://mohammedabdelshafy.github.io/creator-growth-stack/lead-cleanup/
- Sitemap (project path, **not** host root): https://mohammedabdelshafy.github.io/creator-growth-stack/sitemap.xml
- Existing hosted inquiry form: https://clipform.io/7f9689f00

## Publishing checklist
1. Review all marketing claims and the exact service scope. No published customer proof, full video-clipping capability, payment readiness, or deliverability verification is asserted.
2. Confirm the Clipform is **owned by MBM**, submission notification is connected, data handling terms exist, and a dry-run submission reaches the intended recipient. Accessibility of a public form does not prove ownership.
3. Inspect responsive/mobile styles; run HTML accessibility and URL tests.
4. Confirm GitHub Pages source matches repository root on `main` and that deployed links resolve.
5. Verify the relevant URL-prefix property in Google Search Console, then register it in GSC Wizard; submit `sitemap.xml` after publishing and verification.
6. Connect privacy-appropriate first-party analytics only after confirming ownership, notice/consent configuration and the appropriate project.
7. Track **consented inquiries → qualified conversations → accepted diagnostics → paid pilots**. Do not report crawler counts as visitors or unverified chat records as paying customers.

## Why no robots.txt?
GitHub Pages project paths use `/creator-growth-stack/`. A `robots.txt` within that subpath does **not** act as the host's root `/robots.txt`. This PR uses page-level robots directives and a project-path sitemap instead. The latter should be submitted through the correct Search Console property.

## No automation of outreach
This PR only adds content and site-discovery assets. No leads are scraped, no ads purchased, no API keys stored, no messages sent, no production deploys requested.
