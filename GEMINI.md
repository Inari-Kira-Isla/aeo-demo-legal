# aeo-demo-legal

## Overview
A legal industry website template focused on AI Engine Optimization (AEO). It demonstrates how to structure content for LLMs and AI agents using Schema.org JSON-LD, semantic HTML, and machine-readable text files.

## Tech Stack
- HTML5 (Semantic Markup)
- JSON-LD (Schema.org)
- llms.txt (AI Context Protocol)
- CSS (Minimal/Responsive)

## Architecture
- `index.html`: Main entry point containing legal content and structured data.
- `llms.txt`: A text file specifically designed for LLMs to understand the site's purpose and structure.
- `faq.html`: Dedicated FAQ section with optimized markup.

## Commands
- **Preview**: Open `index.html` directly in a web browser.
- **Validation**: Run HTML validation to ensure semantic tags are correct.
- **Testing**: Use Google's Rich Results Test or Schema Markup Validator to verify JSON-LD.

## Coding Style
- Strict semantic HTML5 structure.
- Use `application/ld+json` for all Schema data.
- Keep content concise for AI consumption.
- Ensure `robots.txt` and `llms.txt` are present and valid.

## Important Rules
- **Mandatory Markup**: Do not remove Schema.org JSON-LD blocks from any page.
- **File Integrity**: Maintain `llms.txt` in the root directory; update it whenever site content changes significantly.
- **Content**: Legal content must be accurate and up to date; AI-generated placeholders should be replaced with real text.