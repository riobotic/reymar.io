# reymar.io

Personal portfolio for Mario Reynoso, rebuilt as a fast, responsive, accessible static site.

## Run locally

```bash
npm start
```

Then open `http://localhost:8080`.

## Stack

- Semantic HTML
- Modern CSS
- Vanilla JavaScript
- No build step

## Security and deployment

Netlify is configured in `netlify.toml` with HTTPS canonicalization, a restrictive
Content Security Policy, anti-framing and MIME-sniffing protections, a limited
browser permissions policy, and strict transport security.

The custom domain must have a valid Netlify-managed TLS certificate before HTTPS
can be considered healthy.
