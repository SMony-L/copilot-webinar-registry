# Copilot Enablement Series — Webinar Registry

A public-facing GitHub Pages site hosting registration links for the GitHub Copilot Enablement Series webinars.

## 🔗 Live Site

[https://smony-l.github.io/copilot-webinar-registry/](https://smony-l.github.io/copilot-webinar-registry/)

## Sessions

| Series | Dates | Time |
|--------|-------|------|
| **Getting Started** with GitHub Copilot | Mar 9, 13, 23, 27 | 1:00 PM EST |
| **Level Up** with GitHub Copilot | Mar 16, 20, 30 / Apr 3 | 1:00 PM EST |
| **Copilot Office Hours** | Mar 11, 25 | 1:00 PM EST |
| **Product Release Updates** | Mar 12, 26 | 1:00 PM EST |

## Updating Registration Links

Edit `index.html` and replace the `href="#"` and `class="coming-soon"` on any date's `<a>` tag:

```html
<!-- Before -->
<a href="#" class="coming-soon">Link Coming Soon</a>

<!-- After -->
<a href="https://your-registration-link.com">Register →</a>
```

Changes pushed to `main` will automatically deploy via GitHub Pages.
