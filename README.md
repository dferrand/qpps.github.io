# Quantum Powered POWER sizer

Quick sizer for IBM POWER servers.

Reference of CPW and rPerf rating for current and older IBM POWER servers.

Available at [https://qpps.github.io](https://qpps.github.io).

Based on [IBM Power Performance Report](https://www.ibm.com/downloads/cas/K90RQOW8) and [IBM Power Performance Capabilities Reference](https://www.ibm.com/downloads/cas/LGMXGGPJ).

NOT an official IBM tool.

This tool is provided as is without warranty of any kind. Refer to IBM, your business partner and/or official IBM documentation.

Currently beta software.

## Development

Requires Node.js 18 or later.

```sh
npm ci
npm run dev      # local dev server
npm run check    # svelte-check
npm run build    # static site written to ./build
```

## Deployment

Pushes to `main` are built and deployed to GitHub Pages by `.github/workflows/deploy.yml`.
In the repository settings, set Pages > Source to "GitHub Actions". The site is served from the
domain root, so the repository must be named `<owner>.github.io`.
