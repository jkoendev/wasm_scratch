# wasm_scratch


try:
```
python -m SimpleHTTPServer 8080
emcc hw.c
emcc hw.c -o hw.html
emcc hw.c -s WASM=0 
node hw.out.js
em++ sdl.c -o sdl.html

```

