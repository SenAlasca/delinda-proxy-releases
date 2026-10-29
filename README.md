# De Linda Proxy releases

Public installers for [De Linda Proxy](https://proxy.delinda.nl).

## Latest release: v0.1.1

- **Windows x64 MSI** — [De.Linda.Proxy_0.1.1_x64_en-US.msi](https://github.com/SenAlasca/delinda-proxy-releases/releases/download/v0.1.1/De.Linda.Proxy_0.1.1_x64_en-US.msi)
- **Windows x64 setup** — [De.Linda.Proxy_0.1.1_x64-setup.exe](https://github.com/SenAlasca/delinda-proxy-releases/releases/download/v0.1.1/De.Linda.Proxy_0.1.1_x64-setup.exe)
- **macOS Apple silicon** — [De.Linda.Proxy_0.1.1_aarch64.dmg](https://github.com/SenAlasca/delinda-proxy-releases/releases/download/v0.1.1/De.Linda.Proxy_0.1.1_aarch64.dmg)
- **macOS Intel** — [De.Linda.Proxy_0.1.1_x64.dmg](https://github.com/SenAlasca/delinda-proxy-releases/releases/download/v0.1.1/De.Linda.Proxy_0.1.1_x64.dmg)

Or open the [latest release](https://github.com/SenAlasca/delinda-proxy-releases/releases/latest).

## Requirements

- A De Linda account. Guests can browse, but only a signed-in account can connect.
- All risk levels are allowed except \BANNED\.
- The desktop app sets your operating system's HTTP/HTTPS and SOCKS proxy. Chrome, Edge, Safari, and default Firefox use it automatically.

## Notes

- The installer and app are called **De Linda Proxy** — not **De Linda VPN**.
- The source repository is private.
- v0.1.1 Windows and macOS builds are unsigned; SmartScreen and Gatekeeper may warn.
- On macOS, right-click → Open, or run \xattr -dr com.apple.quarantine "/Applications/De Linda Proxy.app"\ after moving the app to Applications.
- The app loads its UI from https://proxy.delinda.nl/app and connects directly to the proxy host. Vercel never carries the tunnel.