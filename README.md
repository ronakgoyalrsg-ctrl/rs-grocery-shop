# RS Grocery Shop — Static Single-File Site

Pure HTML/CSS/JS. No build step. No backend. Cart uses localStorage. Checkout redirects to WhatsApp (`wa.me/918239304424`) — no Twilio, no SMS API.

## Files
- `index.html` — पूरा app (एक फ़ाइल)
- `images/` — 29 product images

## Deploy

### Netlify (drag & drop)
1. https://app.netlify.com/drop खोलें
2. पूरा फोल्डर drag करें → live हो जाएगा

### GitHub Pages
1. नया repo बनाएँ, ये files upload करें
2. Settings → Pages → Source: `main` branch, `/root` → Save
3. कुछ मिनट में URL मिल जाएगा

### कोई भी static host (Vercel, Cloudflare Pages, etc.)
- फोल्डर upload करें, `index.html` root पर होना चाहिए। बस।

## WhatsApp Number बदलना
`index.html` में line search करें: `WHATSAPP_NUMBER = "918239304424"` — अपना नंबर डालें (country code + number, no +).
