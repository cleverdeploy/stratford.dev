# stratford.dev

Static site promoting a startup culture in the West Midlands — networking, helping founders, and using AI in Stratford-upon-Avon.

## Run locally

```bash
cd /home/wasim/projects/stratford.dev/website
python3 -m http.server 8090 --bind 0.0.0.0
```

Then open <http://localhost:8090> (or <http://192.168.122.242:8090> from the host).

## Files

```
index.html       # Landing — mission + three pillars + contact
networking.html  # Founder networking / introductions / meetups
ai.html          # Using AI in Stratford-upon-Avon
about.html       # What this is, what it isn't, contact
styles.css       # Single shared stylesheet (light civic palette)
```

No build step, no JS, no dependencies. Fonts loaded from Google Fonts (Fraunces for headings, system sans for body).

## Contact

- Email: info@stratford.dev
- Phone: 020 7205 4332
