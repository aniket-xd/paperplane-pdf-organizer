# Paperplane PDF Organizer

An offline-first Windows desktop app for arranging and cleaning up PDF pages. Paperplane makes splitting visual: inspect every page thumbnail and place an upward-facing scissors marker wherever a new file should begin.

## Features

- Merge PDFs and add images as pages
- Split at page markers; save numbered PDFs directly to a chosen folder
- Rotate, delete, extract, and reorder pages
- Compress toward a target file size
- Deshadow scans with before/after previews and A4 or Legal export

PDF processing happens locally. The app uses GitHub Releases to check for updates.

## Download

See [Releases](https://github.com/aniket-xd/paperplane-pdf-organizer/releases) for Windows installers.

## Build

Requires Windows 10/11, Node.js 22, Rust, Microsoft C++ Build Tools, and WebView2.

```powershell
npm ci
npm run tauri -- build --bundles msi
```

The MSI is written to `src-tauri/target/release/bundle/msi/`.

## Contributing

Issues and pull requests are welcome. Please include reproduction steps for bugs and explain the user-facing impact of changes. See [CONTRIBUTING.md](CONTRIBUTING.md) and [SECURITY.md](SECURITY.md). Never commit documents containing personal data, credentials, or updater signing keys.

## License and credits

Original Paperplane code is released under the [MIT License](LICENSE). Maintained by Aniket Aggarwal, with development assistance from OpenAI Codex. Third-party notices are in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

Paperplane is independent and is not affiliated with Smallpdf or Lensup. It does not include their proprietary source code or branding.
