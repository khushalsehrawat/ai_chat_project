# ai_chat_project

## Project

A plain HTML/CSS/JavaScript chat interface with a Spring Boot WebSocket backend in `GenieAi/`. The interface supports conversations, saved chat sessions and sentiment charts. Chart.js is loaded from a CDN.

Serve the repository with a static web server to preview the UI. Chat responses require the existing backend and its configured AI service. The current frontend connects to `ws://localhost:8080/chat`. This metadata update does not change the AI integration or application configuration.

## Website metadata

`index.html` preserves the Gemini AI Chat title and includes a description, TheBenzzCreations author/creator metadata, Open Graph metadata, Twitter card metadata and one WebApplication JSON-LD block identifying the developer.

One visible developer credit appears beneath the chat input, including when the sidebar is hidden on mobile. Its developer link uses a normal same-tab hyperlink. The attribution identifies the application developer and does not claim affiliation with the AI provider.

The public frontend URL has not been verified. Canonical links, `og:url` and the application's structured-data `url` are omitted until that URL is confirmed. Do not use the backend endpoint or developer website as the application's canonical URL. No dedicated social preview image is configured. Structured data does not guarantee search rich results.

There is no frontend package manifest, configured lint suite or build command. Backend-dependent behavior requires a running backend and its configured services.

## Development & Maintenance

**Developed & Maintained by
[Khushal Sehrawat](https://github.com/khushalsehrawat)**
— Founder of
[TheBenzzCreations](https://www.thebenzzcreations.com/).

TheBenzzCreations is a digital development studio specializing in website development, custom software, mobile applications, e-commerce solutions and AI-powered business automation.

For development enquiries and collaborations, visit [TheBenzzCreations](https://www.thebenzzcreations.com/).
