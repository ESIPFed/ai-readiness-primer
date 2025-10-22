# AI Readiness Primer

A primer resource for AI readiness in the community, hosted as a Quarto website via GitHub Pages.

## About

This repository hosts resources consolidated into a primer for community use. The site is built using [Quarto](https://quarto.org/) and automatically published to GitHub Pages.

## View the Site

The published site is available at: https://esipfed.github.io/ai-readiness-primer/

## Local Development

### Prerequisites

- [Quarto](https://quarto.org/docs/get-started/) installed on your system

### Building Locally

To preview the site locally:

```bash
quarto preview
```

To render the site:

```bash
quarto render
```

The rendered site will be in the `_site` directory.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a new branch for your changes
3. Make your changes to the `.qmd` files
4. Test locally with `quarto preview`
5. Submit a pull request

## Project Structure

- `_quarto.yml` - Quarto project configuration
- `index.qmd` - Homepage content
- `about.qmd` - About page content
- `styles.css` - Custom CSS styles
- `.github/workflows/publish.yml` - GitHub Actions workflow for publishing

## Deployment

The site is automatically built and deployed to GitHub Pages when changes are pushed to the `main` branch. The workflow uses GitHub Actions and the official Quarto action.