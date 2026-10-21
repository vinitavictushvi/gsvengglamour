# GSV — Beauty Beyond Expectations (static frontend)
1. **Open**: double-click `index.html`. Pages: Home, Services, Gallery, Prices, Book Appointment (`booking.html`), Contact.
2. **Services / prices / durations**: edit `PRICES` and the `RAW`/`DESC` objects at the top of `js/script.js`. Missing prices show "Price on request".
3. **Images**: see `assets/images/README.md`.
4. **WhatsApp & contact details**: fill `CONFIG` at the top of `js/script.js` (`whatsapp` as digits with country code, e.g. 919XXXXXXXXX). Empty values show "not configured".
5. **Demo booking**: validates, makes a reference, saves to this browser's localStorage only, and shows "Request prepared". Nothing reaches GSV until the customer sends the prefilled WhatsApp message. Not a confirmed booking; no availability, payments, SMS or email.
6. **Limits**: no backend; localStorage is per-browser, not a customer database. Testimonials are labelled sample content; policies are placeholders.
7. **Colours/fonts**: CSS variables at the top of `css/style.css`. Fonts load from Google Fonts if online, with system fallbacks offline.
8. **Deploy**: upload the folder to any static host (Netlify, GitHub Pages, etc.).
