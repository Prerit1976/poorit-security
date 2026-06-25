# Cybersec 101 — Intro for Engineering Students

A self-contained, single-file HTML lecture companion giving engineering students a 100-minute crash course in cybersecurity.

**Live site:** https://prerit1976.github.io/poorit-security/

## What's inside

- Course intro, expectations, and career opportunities (with real salary bands)
- Importance of security — CIA triad, impact cards
- Threats vs. Vulnerabilities vs. Risks
- Password & brute-force attacks — interactive crack-time estimator
- Real breaches timeline — Target, Equifax, WannaCry, SolarWinds, Colonial Pipeline, MOVEit, AIIMS Delhi
- Exposure & attack surface — custom SVG map
- 4 hands-on labs (all run client-side, nothing leaves the browser):
  1. Phishing URL Spotter game
  2. SHA-256 Avalanche-effect visualizer
  3. SQL Injection Playground
  4. Caesar Cipher (encrypt/decrypt/brute-force)
- 5-question quiz with explanations
- 16 curated free learning resources

## Local development

It's a single HTML file. Just open `index.html` in a browser, or:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

Pushed to `main` → GitHub Pages workflow rebuilds automatically.
