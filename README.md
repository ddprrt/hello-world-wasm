# Hello World in WASM

Build & Run:
1. `cargo install wasm-pack`
2. `wasm-pack build --target web`
3. `cp ./static/index.html ./pkg`
4. `cd pkg && php -S localhost:8000`
