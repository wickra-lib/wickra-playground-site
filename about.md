# About Wickra Playground

Run one StrategySpec live, side by side, byte-identical in Rust, JS, Go and Python — entirely in your browser, with no backend.

## What it does

The playground takes one `StrategySpec` and runs it four times over the same candles: compiled to WebAssembly from Rust, driven from JavaScript over that WASM, driven from Go over it, and driven from Python through Pyodide. It then shows the four reports side by side.

## Why it exists

Cross-language consistency is easy to assert and hard to show. Four independent runtimes producing the same report, live and in front of you, is the demonstration — not a paragraph in a README.

## Open source

Released under the **MIT OR Apache-2.0** license — permissive, OSI-approved and
free for any use, including commercial. Source, issues and releases on
[GitHub](https://github.com/wickra-lib/wickra-playground).

## Disclaimer

Wickra Playground is software, **not** a trading system, and is provided **as-is with no
warranty**. It does not give financial advice. Use it at your own risk.
