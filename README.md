# Scanner

A high-performance CSS class scanner extracted from Tailwind CSS. This package is used internally by [Sugarcube](https://github.com/sugarcube-org) to scan and extract CSS classes from various file formats and template languages.

## Crates

- **`oxide`** - Core scanning engine for file discovery and class extraction
- **`ignore`** - File ignore pattern matching (gitignore-compatible)
- **`classification-macros`** - Procedural macros for classification
- **`node`** - Node.js bindings for the Rust crates

## Building

```bash
# Install dependencies
pnpm install

# Install Rust target
rustup target add wasm32-wasip1-threads

# Build everything
pnpm run build
```

## Publishing

```bash
pnpm run publish
```

## License

MIT License. Portions derived from Tailwind CSS (Tailwind Labs, Inc.).