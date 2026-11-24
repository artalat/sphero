# Sphero BOLT Controller

A game-controller style web app for driving a Sphero BOLT over Bluetooth, right from the browser.

**Live:** https://sphero.artalat.com

## Use it
- **Android / Windows / Mac:** open in Chrome or Edge, tap **Connect BOLT**, pick the device starting with `SB-`.
- **iPhone / iPad:** Safari has no Web Bluetooth — open it in the free **Bluefy** browser.
- Tap **🎯 Aim** first and turn the dial until the blue tail light faces you.

## Controls
| Control | Action |
|---|---|
| Left stick | Drive |
| A | Boost |
| B | Stop |
| X | Next colour |
| Y | Face on the LED matrix |
| L / R | Spin |
| 🐢 🐇 🚀 | Speed mode |
| 💬 | Scroll a message |

Physical Xbox / PlayStation / Switch controllers work via the Gamepad API.

## Deploy
Static single file (`index.html`). Pushing to `main` deploys automatically on Vercel.
