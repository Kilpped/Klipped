# Klipped
![logo-klipped](/assets/Klipped.png)
> A private, encrypted clipboard sync across all your devices and any browser you sit down at.

Copy on your phone. Paste on any PC. Klipped keeps your clipboard in sync across your entire device ecosystem — native apps, browser extension, peer-to-peer transfers, all end-to-end encrypted.

---

## Repositories

This is the main repository. All platform clients and the relay are maintained as individual repos and included here as submodules.

| Repo | Description |
|---|---|
| `klipped-relay` | Backend — device presence, metadata, WebRTC signalling, pairing |
| `klipped-ios` | iOS & iPadOS app |
| `klipped-macos` | macOS menu bar app |
| `klipped-windows` | Windows system tray app |
| `klipped-extension` | Browser extension (Chrome & Firefox) |

---

## How it works

Klipped has two tiers:

**Your devices** — iPhone, iPad, macOS, Windows. Full clipboard access, auto-sync on copy, works over local network without internet.

**Any browser** — Install the extension on a college PC or library computer. Receive and send clips via the popup or right-click menu. No account sharing required.

Clip content is encrypted on-device before it ever leaves. The relay brokers connections and stores metadata — it never sees your content in plaintext. Large files transfer peer-to-peer via WebRTC.

---

## Status

🚧 Early development.

---

## License
MIT License

TBD