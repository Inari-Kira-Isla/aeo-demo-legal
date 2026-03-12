# aeo-demo-legal

## Project
AEO demo template for legal industry websites using HTML with Schema.org structured data, llms.txt, FAQ markup, and AI-friendly semantic HTML.

## Conventions
- Use semantic HTML5 elements (<article>, <section>, <nav>, <main>)
- Include Schema.org JSON-LD in <script type="application/ld+json"> tags
- Place structured data in <head> or before </body>
- Use accessible HTML attributes (aria-label, role)
- Keep FAQ content in FAQPage schema format
- Maintain llms.txt in project root

## Naming
- Use kebab-case for HTML filenames (legal-services.html)
- Use lowercase for all files
- Use descriptive class names: .legal-content, .faq-section, .schema-data

## Architecture
- Single static HTML pages with embedded CSS/JS
- Schema.org JSON-LD for search engines and AI understanding
- llms.txt serves as AI agent index
- FAQPage schema for question-answer content
- Legal-specific structured data (Lawyer, LegalService, Organization)

## Commands
- No build commands required (static HTML)
- Validate HTML: https://validator.w3.org/
- Test structured data: https://search.google.com/test/rich-results

## Do Not
- Do not remove Schema.org markup from pages
- Do not use non-semantic <div> soup
- Do not skip accessibility attributes
- Do not remove llms.txt from repository root
- Do not add client-side frameworks — keep it static HTML