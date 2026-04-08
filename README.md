# Mirofish Trading PRO+

## Vercel deployment

1. Import the repository into Vercel.
2. Add an environment variable named `VITE_TWELVEDATA_KEY` if you want live market data.
3. Build command: `npm run build`
4. Output directory: `dist`

If no API key is set, the app still builds and runs with fallback demo candles.
