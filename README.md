<div align="center">

  <h1><code>wasm-game-of-life</code></h1>

  <strong>A simple implementation of the game of life using <a href="https://github.com/rustwasm/wasm-pack">wasm-pack</a>.</strong>

  <sub>Built with 🦀🕸 by <a href="https://rustwasm.github.io/">The Rust and WebAssembly Working Group</a></sub>
</div>


## 🚴 Usage

### 🐑 Use `wasm-pack build` to build wasm binaries

[Learn more about `wasm-pack` here.](https://github.com/rustwasm/wasm-pack">wasm-pack)

```
wasm-pack build
```

### 🛠️ navigate to the www folder, run `npm install` after installation `npm run start`

```
npm install && npm run start
```

### 🔬 Test in Headless Browsers with `wasm-pack test`

```
wasm-pack test --headless --firefox
```

## 🔋 Batteries Included

* [`wasm-bindgen`](https://github.com/rustwasm/wasm-bindgen) for communicating
  between WebAssembly and JavaScript.
* [`console_error_panic_hook`](https://github.com/rustwasm/console_error_panic_hook)
  for logging panic messages to the developer console.
* [`wee_alloc`](https://github.com/rustwasm/wee_alloc), an allocator optimized
  for small code size.
