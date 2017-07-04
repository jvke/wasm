This is a *very* simple experimental use of WASM.
If you'd like to clone/fork & play with it locally, you'll need to run a local webserver using `dist/` as your root, as the `fetch` API doesn't support `file://` refs.

I used https://mbebenita.github.io/WasmExplorer/ to compile from C to WAST, then from WAST to a WASM binary. Current plans are to get Emscripten set up to have a nicer build flow.
