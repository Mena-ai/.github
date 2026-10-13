## 2025-04-20 - LLM-generated Citation Markers Impact on A11y
**Learning:** Raw LLM-generated citation markers (e.g., `([mena-ai.pt][1])`) in markdown documentation create visual clutter and severely degrade the experience for screen reader users by introducing unnecessary, hard-to-parse elements.
**Action:** Always replace raw citation markers with clean, descriptive inline links in markdown documentation to prevent visual clutter and improve screen reader accessibility.
## 2023-10-13 - Descriptive Links in Static Markdown
**Learning:** Markdown documentation lacks native ARIA support, making descriptive link text crucial for screen reader accessibility and preventing LLM-generated raw URLs from cluttering the reading experience.
**Action:** Always rewrite generic link text (e.g., "Get Started »") and raw URLs into descriptive, context-rich labels, and strip out unnecessary tracking parameters from URLs to keep them clean.
