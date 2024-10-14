## Getting Started

This project was built using [Docusaurus](https://docusaurus.io/). Read more about the installation process [here](https://docusaurus.io/docs/installation).

### Requirements

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.
- npm

## Build

To build the website use

```bash
npm run build
```

This command generates static content into the `build` directory.

## Testing your build locally

To test your build locally, run the following command:

```bash
npm run serve
```

By default, this will load your site at http://localhost:3000/.

## Adding a new page

This project only uses documentation pages. To add a new page, create a new markdown file in the `docs` directory. The file should have a `.md` extension.

Read [Docs Introduction](https://docusaurus.io/docs/docs-introduction) for more information on how to create documentation pages.

## Deployment (github pages) (github actions)

This project is set up to deploy to GitHub Pages using GitHub Actions. All changes to the `main` branch will trigger the GitHub Actions to build and deploy the website.