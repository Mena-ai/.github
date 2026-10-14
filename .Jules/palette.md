## 2025-04-20 - LLM-generated Citation Markers Impact on A11y
**Learning:** Raw LLM-generated citation markers (e.g., `([mena-ai.pt][1])`) in markdown documentation create visual clutter and severely degrade the experience for screen reader users by introducing unnecessary, hard-to-parse elements.
**Action:** Always replace raw citation markers with clean, descriptive inline links in markdown documentation to prevent visual clutter and improve screen reader accessibility.
## 2026-10-14 - Remove Tracking Parameters and Generic Link Texts for A11y
**Learning:** Including tracking parameters in URLs (e.g. `?utm_source=`) and generic link texts (e.g. "Get Started »") in markdown documentation introduces visual clutter and makes navigation difficult for screen reader users, who rely on clear, descriptive link texts to understand the link's destination.
**Action:** Always replace generic link texts with descriptive alternatives (e.g. "View Mena.ai Pricing and Plans") and strip unnecessary tracking parameters from markdown links.
