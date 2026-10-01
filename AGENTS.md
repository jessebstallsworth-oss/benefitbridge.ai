# BenefitBridge AI — Base44 Dev Environment

## Project overview
Single-file static HTML mockup (`index.html`) for the BenefitBridge AI insurance app. No backend, no build system, no dependencies.

## Running the app
`docker compose -f docker-compose.base44.yml up -d` — serves `index.html` via nginx:alpine on host port 3000.

## Verification
- `curl -s http://localhost:3000/ | head -5` should return the HTML doctype and `<title>BenefitBridge AI Mockups</title>`.
- The page is a mockup with light/dark theme toggle and scroll-spy navigation. No interactive backend.

## Secrets
None required.
