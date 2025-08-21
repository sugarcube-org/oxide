# Tailwind Oxide

This repository contains the Rust crates that power Tailwind Oxide's core functionality.

## Crates

- **`oxide`** - Core Tailwind CSS processing logic
- **`ignore`** - File ignore pattern matching
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
