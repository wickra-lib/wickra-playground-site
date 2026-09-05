---
layout: home
title: "Wickra Playground — A polyglot strategy playground: one StrategySpec run live and side by side in Rust, JS, Go and Python, entirely in the browser over WebAssembly"
titleTemplate: false

hero:
  name: "Wickra Playground"
  text: "Four languages. One answer."
  tagline: "Run one StrategySpec live, side by side, byte-identical in Rust, JS, Go and Python — entirely in your browser, with no backend."
  image:
    src: /wickra-mark.svg
    alt: "Wickra Playground"
  actions:
    - theme: brand
      text: View on GitHub
      link: https://github.com/wickra-lib/wickra-playground
    - theme: alt
      text: How it works
      link: /about

features:
  - icon: 🧪
    title: "Proof, not a claim"
    details: "Every backtest library claims cross-language consistency. The playground runs one spec through the same Rust core along four independent paths and puts the four reports next to each other."
  - icon: 🌐
    title: "No backend at all"
    details: "Rust→WASM, JS-over-WASM, Go-over-WASM and Python-over-Pyodide all run in the tab. Nothing is uploaded, and nothing is computed on a server."
  - icon: 📄
    title: "The strategy is data"
    details: "A StrategySpec is a JSON document, not code, so the identical file crosses every runtime unchanged — which is what makes the comparison meaningful."
  - icon: ⚙️
    title: "The engine underneath"
    details: "Built on wickra-backtest, the deterministic engine behind the rest of the stack, over the Wickra core's 514 indicators."
---
