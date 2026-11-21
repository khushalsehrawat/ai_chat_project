# ai_chat_project

## Project

A plain HTML/CSS/JavaScript chat interface with a Spring Boot WebSocket backend in `GenieAi/`. The interface supports conversations, saved chat sessions and sentiment charts. Chart.js is loaded from a CDN.

Serve the repository with a static web server to preview the UI. Chat responses require the existing backend and its configured AI service. The current frontend connects to `ws://localhost:8080/chat`. This metadata update does not change the AI integration or application configuration.

## Website metadata

`index.html` preserves the Gemini AI Chat title and includes a description, TheBenzzCreations author/creator metadata, Open Graph metadata, Twitter card metadata and one WebApplication JSON-LD block identifying the developer.

One visible developer credit appears beneath the chat input, including when the sidebar is hidden on mobile. Its developer link uses a normal same-tab hyperlink. The attribution identifies the application developer and does not claim affiliation with the AI provider.

Production identity is recorded in `seo-sites.json`; see Canonical URL validation below. The developer credit is not evidence of a project deployment URL.

There is no frontend package manifest, configured lint suite or build command. Backend-dependent behavior requires a running backend and its configured services.

## Development & Maintenance

**Developed & Maintained by
[Khushal Sehrawat](https://github.com/khushalsehrawat)**
— Founder of
[TheBenzzCreations](https://www.thebenzzcreations.com/).

TheBenzzCreations is a digital development studio specializing in website development, custom software, mobile applications, e-commerce solutions and AI-powered business automation.

For development enquiries and collaborations, visit [TheBenzzCreations](https://www.thebenzzcreations.com/).

## Canonical URL validation

Run `python scripts/validate_seo.py` from this repository before publishing. The dependency-free check validates exact page canonicals, Open Graph URLs, website/application JSON-LD URLs, sitemap locations, robots sitemap references and literal framework site metadata against `seo-sites.json`. It checks deployment path prefixes as well as domains, so one GitHub Pages project cannot canonicalize to another.

Only URLs whose live HTML matched the local page on 2026-11-21 are configured. Unverified pages have no canonical or social URL; `python scripts/validate_seo.py --require-verified` also fails for those pending pages. Reverify the configuration if the deployment moves. Dynamic framework expressions still require runtime validation.

TheBenzzCreations attribution, creator organization URLs and existing normal same-tab developer credit links are preserved. These outbound attribution links are separate from site identity.
