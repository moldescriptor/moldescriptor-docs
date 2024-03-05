## Getting Started

This project was built using [Docusaurus](https://docusaurus.io/). Read more about the installation process [here](https://docusaurus.io/docs/installation).

### Requirements

- [Node.js](https://nodejs.org/en/download/) version 18.0 or above:
  - When installing Node.js, you are recommended to check all checkboxes related to dependencies.
- npm

## Starting the website

Run the development server:

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

## Build

To build the website use

```bash
npm run build
```

This command generates static content into the `build` directory.

## Adding a new page

This project only uses documentation pages. To add a new page, create a new markdown file in the `docs` directory. The file should have a `.md` extension.

Read [Docs Introduction](https://docusaurus.io/docs/docs-introduction) for more information on how to create documentation pages.