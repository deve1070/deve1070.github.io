# Portfolio on Vercel

This app is ready for Vercel deployments.

## Vercel settings
- Root directory: `portfolio`
- Install: `npm install`
- Build: `npm run build`
- Output: `build`
- Framework: Create React App
- `vercel.json` already rewrites all routes to `index.html` for SPA routing.

## Deploy with CLI (optional)
```
cd portfolio
vercel --prod --cwd .
```

## Notes
- `homepage` was removed from `package.json` so asset paths work on Vercel.
- GitHub Pages deploy is still available via `npm run deploy` if needed.
