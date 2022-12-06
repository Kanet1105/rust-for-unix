# Fyrox Webassembly Template
## Instructions
1. Clone the repo. 
```
git clone https://github.com/Kanet1105/fyrox-wasm-template.git
```
2. Get "wasm32-unknown-unknown" target installed. 
```
rustup target add wasm32-unknown-unknown
```
3. Install "wasm-pack", if you hadn't done so.
```
cargo install wasm-pack
```
4. Install "basic-http-server" (and build with wasm-pack instead of "Trunk").
```
wasm-pack build --target web
basic-http-server
```
