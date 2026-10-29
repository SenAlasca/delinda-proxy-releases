# De Linda Proxy releases

Public installers for [De Linda Proxy](https://proxy.delinda.nl).

## Download

Open the [latest release](https://github.com/SenAlasca/delinda-proxy-releases/releases/latest) and choose:

- **Windows x64** — the NSIS setup.exe is the simplest installer; the .msi is available for managed deployments.
- **macOS** — builds are produced by the release workflow and published here when available.

## Requirements

- A De Linda account. Guests can browse, but only a signed-in account can connect.
- All risk levels are allowed except BANNED.
- The desktop app sets your operating system's HTTP/HTTPS and SOCKS proxy. Chrome, Edge, Safari, and default Firefox use it automatically.

## Notes

- The source repository is private. Release notes are the place to check build and signing details.
- Current Windows builds are unsigned, so SmartScreen may warn. Verify the download came from this repository.
- The app loads its UI from https://proxy.delinda.nl/app and connects directly to the proxy host. Vercel never carries the tunnel.