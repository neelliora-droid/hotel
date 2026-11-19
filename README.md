# Neel Liora website

React + Vite + Tailwind CSS + Framer Motion + Lucide.

    npm install
    npm run dev       # local preview
    npm run build     # production build in /dist

## Before launch (all in `src/config/site.js`)
- `whatsappNumber` (digits only, with country code), `phone`, optional `email`
- `bookingComUrl`, `airbnbUrl`
- `mapsUrl` and `mapsEmbedUrl` (Google Maps > Share > Embed a map > copy the `src` value). Use the verified location only.
- Real photos into `public/images/` (see the README there). Compress them first.

Until a value is set, its button stays visible and tells the visitor the link isn’t set up yet.
The WhatsApp booking only opens a pre-filled chat. The guest presses Send and the owner confirms availability and price.
