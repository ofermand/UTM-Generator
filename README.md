# AlgoSec UTM Generator

Static web application for generating clean UTM links for AlgoSec Marketing campaigns.

## Deploy to Vercel

### Option 1: Upload folder manually
1. Go to Vercel.
2. Create a new project.
3. Upload or import this folder.
4. Framework preset: **Other**.
5. Build command: leave empty.
6. Output directory: leave empty.
7. Deploy.

### Option 2: Vercel CLI
```bash
npm install
npx vercel
```

## Files

- `index.html` — the full static application.
- `vercel.json` — deployment configuration and basic security headers.
- `package.json` — optional local Vercel development script.

## Notes

- UTM history is stored in the user's browser via `localStorage`.
- No backend or database is required.
