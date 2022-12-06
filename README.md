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
> :warning: **If you are on Windows, "openssl" crate fails to build
>  due to the path separator being "\\". Instead of running the cargo command,
>  download the windows binary for wasm-pack from the following link.**

https://rustwasm.github.io/wasm-pack/installer/

4. Install "basic-http-server" (and build with wasm-pack instead of "Trunk").
```
wasm-pack build --target web
basic-http-server
```

