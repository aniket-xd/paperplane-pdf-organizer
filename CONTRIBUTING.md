# Contributing

Thanks for helping improve Paperplane PDF Organizer.

## Before you start

- Search existing issues and discussions before opening a new one.
- For a large change, open an issue first to agree on the scope.
- Keep pull requests focused and describe how someone can see the change.

## Development

Install Node.js 22, Rust, Microsoft C++ Build Tools, and WebView2. Then run:

```powershell
npm ci
npm run dev
```

Build the Windows installer with:

```powershell
npm run tauri -- build --bundles msi
```

## Pull requests

Include a short summary, the reason for the change, and any manual verification performed. For UI changes, screenshots are helpful. Do not commit generated installers, `node_modules`, PDFs containing personal information, credentials, updater signing keys, or `.env` files.

## Reporting bugs

Include your Windows version, app version, steps to reproduce, and expected versus actual behavior. Remove private document contents and metadata from screenshots or logs.
