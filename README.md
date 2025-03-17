# TwoBirdsPress - Digital Marketing Solutions

This repository contains the deployed static version of the TwoBirdsPress website, a digital marketing agency site built with React, TypeScript, and Tailwind CSS.

## Website Structure

The website is a Single Page Application (SPA) built with React and deployed on GitHub Pages. It includes:

- Main landing page with service information
- Privacy Policy page
- Terms of Service page
- Contact form (static version)

## Technology Stack

- React
- TypeScript
- Tailwind CSS
- Vite (for building)
- GitHub Pages (for hosting)

## Deployment Information

This site is deployed as a static build on GitHub Pages at: [nlapi.github.io/better-faster-media](https://nlapi.github.io/better-faster-media/)

### SPA Routing on GitHub Pages

Since this is a single-page React application with client-side routing deployed on GitHub Pages, we use a special configuration to handle direct URL access:

1. A custom `404.html` that redirects all requests to the main `index.html` with the original path preserved
2. A script in `index.html` that processes the redirected URL and restores the correct route

This allows direct access to URLs like `/privacy-policy` and `/terms-of-service` even though GitHub Pages doesn't natively support SPA routing.

## Updating the Website

To update this website:

1. Make changes to the source code in the original repository
2. Run the static build process: `npm run build-static`
3. Copy the contents of the `static-build` directory to this repository
4. Ensure the `404.html` file is preserved for client-side routing
5. Push the changes to GitHub

## Contact

For any questions regarding this website, please email nisjetl@gmail.com
