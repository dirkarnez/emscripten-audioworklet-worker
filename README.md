[emscripten-audioworklet-worker](https://dirkarnez.github.io/emscripten-audioworklet-worker)
============================================================================================
### Notes
- `Module.onRuntimeInitialized` is not allowed if `int main()` is used (because emscripten compiles it to [IIFE](https://developer.mozilla.org/zh-TW/docs/Glossary/IIFE))
