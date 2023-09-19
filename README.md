# zig-wasm-canvas

An example demonstrating Zig interacting with a canvas via JS. It is a port of
one of the official mozilla examples. 

https://developer.mozilla.org/en-US/docs/WebAssembly

Compile with `zig build-lib -dynamic -rdynamic -target wasm32-freestanding -OReleaseSmall main.zig`
