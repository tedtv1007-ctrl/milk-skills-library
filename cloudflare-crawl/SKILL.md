---
name: cloudflare-crawl
description: Use Cloudflare Browser Rendering API (Crawl) to fetch web pages, especially those requiring JS rendering. Use when you need to extract content from modern SPAs or sites with anti-bot protection that standard fetch tools can't handle.
---

# Cloudflare Crawl

This skill uses the Cloudflare Browser Rendering API to "crawl" a URL. It renders the page in a headless browser and returns the result (HTML by default).

## Workflow

1. **Prerequisites**: Ensure `milk-secrets-repo/cloudflare.json` contains `account id` and `api token`.
2. **Execute**: Run `scripts/cf_crawl.py <url>` to start a crawl and wait for the result.
3. **Handle Result**: The script outputs the final JSON result from Cloudflare.

## Troubleshooting

- **400 Error (Unrecognized keys)**: Do not include `markdown: True` in the request body as it may not be supported by the current API version.
- **Auth Error**: Check if the token in `milk-secrets-repo/cloudflare.json` is valid and has "Browser Rendering" permissions.
