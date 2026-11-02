# Third-party notices

Paperplane includes or uses these third-party components. Their authors retain their respective rights and licenses; the MIT license for Paperplane does not replace them.

| Component | Version | License | Notice / license file |
|---|---:|---|---|
| Tauri and official Tauri JavaScript plugins | 2.x | MIT and Apache-2.0 (component-specific) | `node_modules/@tauri-apps/*/LICENSE*` after `npm ci`; Rust crate notices are available through Cargo metadata |
| PDF.js (`pdfjs-dist`) | 3.11.174 | Apache-2.0 | `node_modules/pdfjs-dist/LICENSE` |
| pdf-lib | 1.17.1 | MIT | `node_modules/pdf-lib/LICENSE.md` |
| Vite | 6.x | MIT | `node_modules/vite/LICENSE.md` |

PDF.js standard fonts and character maps may carry additional notices; see the `standard_fonts` and `cmaps` directories within `pdfjs-dist`. The exact installed dependency tree is recorded in `package-lock.json` and `src-tauri/Cargo.lock` when present. Consult those files and the corresponding package license files when redistributing a modified build.
