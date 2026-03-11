# Frontend

This frontend now uses Vite + React + Ionic.

## Scripts

- `npm run dev` - start the Vite dev server
- `npm start` - alias for `npm run dev`
- `npm run build` - create a production build in `dist/`
- `npm run preview` - preview the production build locally

## Environment

Copy `.env.example` to `.env.local` and set:

- `VITE_BACKEND_URL` - backend API endpoint for `/api/bus-info`

If unset, the app falls back to the current deployed AWS API URL.
