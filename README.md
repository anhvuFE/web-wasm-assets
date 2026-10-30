# gomoku-rapfi-engine

Prebuilt **WebAssembly build of [Rapfi](https://github.com/dhbloo/rapfi)** (single-thread, SIMD128, NNUE, freestyle)
mirrored for use by a personal Tampermonkey userscript on papergames.io.

These binaries are published in **[Releases](../../releases)** (not committed to git):

- `rapfi-single-simd128.js` — Emscripten glue
- `rapfi-single-simd128.wasm` — engine
- `rapfi.data` — NNUE weights

## Source & License

Rapfi is **GPLv3**. This repository redistributes compiled artifacts; the corresponding source is:

- Engine source: https://github.com/dhbloo/rapfi
- WASM build scripts / upstream release: https://github.com/lowqen/RapfiWeb (release `engine-3c94c2a9-a4`)

Licensed under the **GNU General Public License v3.0** — see https://www.gnu.org/licenses/gpl-3.0.html
