# Endurunce Landing Page

Marketing landing page for [Endurunce](https://endurunce.nl) — AI-powered running plans with built-in injury recovery.

## Stack

- Static HTML/CSS served by nginx
- Deployed on [Fly.io](https://fly.io) via Docker

## Development

```bash
# Preview locally
docker build -t endurunce-landing .
docker run -p 8080:8080 endurunce-landing
```

Open [http://localhost:8080](http://localhost:8080).

## Deployment

Deploys automatically via Fly.io:

```bash
fly deploy
```

## Structure

```
html/
├── index.html      # Landing page
├── favicon.png     # PNG favicon
├── icon.svg        # SVG favicon
├── logo-dark.svg   # Logo (dark variant)
├── logo-white.svg  # Logo (white variant)
└── robots.txt      # Search engine directives
```
