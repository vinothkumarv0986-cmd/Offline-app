# OfflineConnect
Instagram-style feed (post, like, comment) + 1:1 video calls over local Wi-Fi / phone hotspot. No internet, no npm packages.

## Run
1. Install Node.js 16+ (and openssl for HTTPS) on one laptop/phone (Termux).
2. `node server.js`
3. Everyone joins the same Wi-Fi or hotspot and opens the printed https://IP:8443 link.
4. Accept the certificate warning once (Advanced -> Proceed).

Pick a username, post photos, double-tap to like, open Call tab to video call.
Feed is saved to feed.json.
