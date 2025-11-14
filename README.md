# SolveForce Fiber Internet Microsite

This repository contains the static assets for the [fiberinternet.solveforce.com](https://fiberinternet.solveforce.com/) microsite. The pages highlight SolveForce's dedicated fiber internet services, availability options, and tailored business solutions.

## Project Structure

| File | Description |
| --- | --- |
| [index.html](./index.html) | Landing page introducing SolveForce Fiber Internet with hero messaging, benefits overview, and CTA links. |
| [speeds.html](./speeds.html) | Detailed breakdown of dedicated fiber tiers, managed service add-ons, and a comparison matrix. |
| [availability.html](./availability.html) | Coverage resources describing on-net, near-net, and custom build processes alongside qualification steps. |
| [business.html](./business.html) | Business solutions showcase featuring DIA, private networking, security services, and industry verticals served. |
| [styles.css](./styles.css) | Shared stylesheet that unifies navigation, hero, grid, typography, and card styling across all pages. |
| [CNAME](./CNAME) | Custom domain declaration required for GitHub Pages deployment. |

## Getting Started

To preview the site locally:

```bash
python -m http.server 8000
```

Then open <http://127.0.0.1:8000/index.html> (or any of the other `.html` pages) in your browser.

## Deployment

The site is designed for static hosting on GitHub Pages. Ensure the `CNAME` file remains present so the custom domain resolves correctly. When changes are pushed to the publishing branch, GitHub Pages will rebuild the static site automatically. If new pages are added, make sure they follow the existing document-relative linking convention (e.g., `./page-name.html`).

## Contributing

1. Fork the repository and create a feature branch.
2. Make your updates and run a local preview to verify styling and navigation.
3. Commit your changes with descriptive messages.
4. Open a pull request summarizing the adjustments and reference any related issues.

For questions about SolveForce services, visit the live site at [fiberinternet.solveforce.com](https://fiberinternet.solveforce.com/).
