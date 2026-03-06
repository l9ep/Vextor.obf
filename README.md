# VEXOR — Lua Obfuscator

**vexor.obf** — A powerful, browser-based Lua obfuscator built to protect your scripts from being read, stolen, or reversed.

---

## What is VEXOR?

VEXOR is a free Lua obfuscation tool that transforms your plain Lua scripts into heavily protected, unreadable code — while keeping them fully functional on any executor.

No installs. No signups. Just paste your script and hit obfuscate.

---

## What does it do?

When you run your script through VEXOR, it goes through multiple layers of protection:

- All variable and function names are replaced with visually indistinguishable garbage names
- Every string in your script is encrypted with a unique key and only decrypted at runtime
- All numbers are transformed into complex math expressions
- Dead code is injected throughout to confuse anyone trying to read it
- Function calls are routed through hidden indirection so their targets aren't visible
- Control flow is restructured to break decompiler logic
- A proxy environment wraps the entire script adding another layer of obscurity

Every single run produces a completely unique output — even if you obfuscate the same script twice, the result will be different.

---

## Compatibility

VEXOR output is designed to run on **every executor** — no exceptions. The obfuscated code is pure Lua 5.1 compatible with no dependencies on restricted or version-specific features.

---

## Features

- Paste your script directly or upload a `.lua` file
- Copy the obfuscated output or download it as a `.lua` file
- Clear input and output independently
- No levels or settings — one click, maximum protection every time
- Runs entirely in your browser — your scripts are never sent anywhere

---

## Credits

Made by **Yuki**  
Discord: `y4zr`
