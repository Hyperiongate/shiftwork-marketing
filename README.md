# Shiftwork Solutions — Marketing Intelligence Dashboard

A personal marketing orchestration tool for finding speaking engagements, article submission opportunities, and generating marketing ideas — powered by Claude AI.

## What It Does

**Speaking Engagements Tab**
Searches for conferences, retreats, roundtables, and trade show speaking slots across target industries (food & beverage, manufacturing, logistics, automotive, pharmaceutical, semiconductor, distribution). Returns 5 opportunities per search with full detail briefings on demand.

**Writing Opportunities Tab**
Finds trade publications and online outlets actively accepting guest article submissions on topics relevant to Shiftwork Solutions — workforce management, shift scheduling, AI in operations, part-time labor.

**Ideation Tab**
Open chat interface for brainstorming marketing strategies, positioning, outreach ideas, and new approaches for Shiftwork Solutions and its products.

## Setup

### Local Development
Just open `index.html` in a browser. On first load, enter your Anthropic API key when prompted. It saves locally.

### Render Deployment
1. Push this repo to GitHub
2. Create a new Render project (Static Site)
3. Connect to this GitHub repo
4. Build command: *(leave blank)*
5. Publish directory: `.`
6. Deploy

No build step required. Pure HTML/CSS/JS.

### API Key
This app uses the Anthropic Claude API directly from the browser. You will need a valid Anthropic API key (`sk-ant-...`).

Enter it on first load — it is saved to your browser's localStorage. It is never sent anywhere except directly to Anthropic's API.

## Products Referenced
- **Shiftwork Solutions** — core consulting, workforce scheduling
- **Temporary Labor Tracker** — part-time worker management app
- **Survey in a Box** — self-service employee survey platform

## Tech Stack
- Pure HTML/CSS/JavaScript — no framework, no build step
- Claude Sonnet via Anthropic API
- Google Fonts (DM Sans, DM Mono, Libre Baskerville)
- Deployed as static site on Render
