# wasm_scratch


try:
```
python -m SimpleHTTPServer 8080
emcc hw.c -o hw.out.js
emcc hw.c -o hw.out.html
emcc hw.c -s WASM=0 
node hw.out.js
em++ sdl.c -o sdl.out.html
```
open [http://localhost:8080/sdl.out.html](http://localhost:8080/sdl.out.html) in browser


