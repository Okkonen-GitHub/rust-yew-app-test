# Wasm frontend application build with Rust using [Yew](https://yew.rs/)

It's very simple. Made by following a tutorial, check it out though

## Requirements
- Rust >1.49
- Run `cargo install --locked trunk`
- Run `cargo install wasm-bindgen-cli`
- Run `rustup target add wasm32-unknown-unknown`

## Running the app
- Use `trunk serve` to run development enviroment

## Building and running an optimized version 
- Use `trunk build --release` to build an optimized version
- Then use `python -m http.server 8080 --directory dist/` and open [localhost:8080](localhost:8080)
- You could build the in other ways too check out some [docs](https://yew.rs/getting-started/project-setup#comparison)