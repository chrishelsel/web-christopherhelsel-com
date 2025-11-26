# web-christopherhelsel-com

GitHub Pages–hosted redirect for **christopherhelsel.com**.

This repository serves a single purpose:

> Redirect all traffic from `christopherhelsel.com` (and `www.christopherhelsel.com`) to **`https://chrishelsel.com`**.

There is no app logic, no backend, and no tracking — just a tiny static HTML file that performs a fast redirect.

---

## Overview

- **Source domain:** `christopherhelsel.com`
- **Target URL:** `https://chrishelsel.com`
- **Hosting:** GitHub Pages
- **Stack:** Single static `index.html` with:
  - `<meta http-equiv="refresh">` redirect
  - JavaScript `window.location.replace(...)` fallback
  - Canonical link pointing to the target URL

This pattern is designed to be repeatable for other “alias” domains in the future.

---

## Project Structure

```text
/
└── index.html   # Minimal redirect page
