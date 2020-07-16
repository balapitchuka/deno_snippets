# Deno

* Deno is a runtime for JavaScript and TypeScript that is based on the V8 JavaScript engine and the Rust programming language.

### Run Commands
-  Run basic Deno script without any file system or network permissions (sandbox mode)
    - ```deno run main.ts```
- Explicit flags are required to enable permissions

`
deno run --allow-read --allow-net main.ts
`

