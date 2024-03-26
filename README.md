sudo apt install wabt  
wat2wasm add.wat -o add.wasm  
base64 add.wasm > wasmBase64  
