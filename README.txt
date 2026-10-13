DAILZO WEBSITE / INSTALLABLE PWA DEMO

Files:
- index.html: Dailzo customer demo
- manifest.webmanifest: app name and install settings
- service-worker.js: basic offline caching
- icon.svg: app icon

IMPORTANT:
This is still a demo. Product catalogue, cart and demo orders are stored in the visitor's own browser/device.
It does NOT send real orders to the shop, validate a 4 km delivery radius, process payments, or sync data between phones.
Never advertise it as a live ordering service until a shared backend and secure admin system are connected.

To install as an app:
1. Upload all files to an HTTPS static host (for example GitHub Pages or Netlify).
2. Open the published HTTPS address in Android Chrome.
3. Use Chrome menu (⋮) > Add to Home screen / Install app.

For real orders, next build step is to connect a shared database and secure admin login.
