# FerroSentry Install Worker

Official Cloudflare Worker that dynamically serves the installation script for **FerroSentry** based on the client User-Agent and operating system:

- **Linux / macOS:** `curl -fsSL https://install.ferrosentry.dev | sudo bash`
- **Windows (PowerShell):** `irm https://install.ferrosentry.dev | iex`

## License

Apache-2.0 License.
