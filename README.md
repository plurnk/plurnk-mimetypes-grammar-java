# @plurnk/plurnk-mimetypes-grammar-java

Pre-built `tree-sitter-java` WASM grammar for the [@plurnk/plurnk-mimetypes](https://github.com/plurnk/plurnk-mimetypes) framework.

## install

```
npm i @plurnk/plurnk-mimetypes-grammar-java
```

## what's in here

- **`java.wasm`** — pre-built from the pinned upstream [tree-sitter-java](https://github.com/tree-sitter/tree-sitter-java) commit (SHA in `.grammar-pin`)
- `scripts/build-wasm.mjs` — reproducible rebuild from the pinned source
- `scripts/verify-wasm.mjs` — CI byte-identical reproducibility check

Declares only `web-tree-sitter` as a peer — no native `tree-sitter`, no node-gyp.

## license

MIT. The bundled `java.wasm` is built from the upstream tree-sitter-java grammar; see the pinned commit for that project's attribution.
