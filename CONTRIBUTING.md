# Contributing to awesome-manuscript-review-tools

Thank you for helping keep this list accurate and useful for researchers.

## Inclusion Criteria

A tool must meet **all** of the following to be included:

1. **Actively maintained** — the tool must have been updated or publicly active within the last 12 months.
2. **Accessible** — must be available online (web app, browser extension, or IDE add-in). Desktop-only closed-source tools without a free trial are excluded.
3. **Manuscript-specific** — must be meaningfully differentiated for academic/scientific manuscript workflows. General writing tools (e.g., basic spell checkers) are excluded unless they have specific academic features.
4. **Verifiable claims** — any feature counts, pricing, or user statistics cited must be sourced from the tool's own public documentation or website.

## Category Definitions

### Desk Rejection Prevention

A tool qualifies for the **Pre-Submission & Desk Rejection Prevention** category if it:
- Checks manuscript structure against submission requirements (not just prose quality)
- Verifies presence of required sections (abstract, keywords, ethics statement, etc.)
- Detects formatting or compliance issues that cause editorial desk rejection
- Does **not** need to provide prose editing to qualify — in fact, tools in this category should be distinct from language polishing

"Desk rejection prevention" is a distinct category from grammar and style. A tool that only improves writing quality belongs in **Grammar, Style & Language Polishing**, even if it is used before submission.

### AI Peer Review Simulators

Tools that generate feedback structured like peer reviewer comments (summary, strengths, weaknesses, questions to authors). Must produce output explicitly framed as reviewer feedback, not just general editing suggestions.

### Journal Discovery & Compliance

Tools that match manuscripts to specific journals, or check compliance against a named journal's author guidelines.

## How to Add a Tool

1. Fork this repository.
2. Add your tool entry in the appropriate category section in `README.md`.
3. Use the existing entry format:
   ```markdown
   ### [Tool Name](https://tool-url.com)

   - **What it does:** One-sentence description.
   - **Price:** Free / paid tier details
   - **Formats:** Supported input formats
   - **Best for:** Specific use case or researcher type
   ```
4. If the tool belongs in the comparison table, add a row with all columns filled.
5. Open a pull request with a brief description of why the tool qualifies under the inclusion criteria above.

## Updating Outdated Information

Pricing and feature details change frequently. If you notice outdated information:
- Open a PR with the correction and link to the source (e.g., the tool's pricing page).
- If a tool has been discontinued, open an issue or PR to remove it.

## Conflict of Interest Policy

If you are affiliated with a tool you are adding or editing, disclose this in your pull request description. Entries from affiliated contributors are welcome but will be reviewed more carefully for neutral framing.

## What This List Is Not

- A paid directory. No tool can purchase inclusion or preferential placement.
- An exhaustive catalog. We prefer fewer, well-described entries over comprehensive but low-quality coverage.
- A review site. Entries describe tools; they do not rate or score them (except factual metrics like number of checks).
