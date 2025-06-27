# zapperment-rocks

Website for _zapperment.rocks_ — producer of electronic music

## Development

```bash
npm install
npm run dev
```

## Deployment

This website is automatically deployed to GitHub Pages on every push to the `main` branch.

The deployment process:

1. Builds the production version using `npm run build`
2. Deploys the contents of the `dist` folder to GitHub Pages
3. The site will be available at: `https://zapperment.github.io/`

### Manual Deployment

If you need to deploy manually:

1. Build the project: `npm run build`
2. Push the `dist` folder to the `gh-pages` branch (if using manual deployment)

### Local Preview

To preview the production build locally:

```bash
npm run build
npm run preview
```
