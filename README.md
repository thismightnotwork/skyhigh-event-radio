# SkyHigh Event Radio

Static frontend for the temporary SkyHigh event voice service.

This repository is designed for GitHub Pages and uses the signaling Worker at `wss://voice.skyhighnetwork.co.uk`.

## Deployment

1. In GitHub, open **Settings** → **Pages**.
2. Set the source to **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`.
4. Add `radio.skyhighnetwork.co.uk` as the custom domain.
5. In Cloudflare DNS, create a DNS-only `CNAME` record named `radio` pointing to `thismightnotwork.github.io`.

GitHub Pages will serve this repository at the custom domain once DNS and domain verification complete.
