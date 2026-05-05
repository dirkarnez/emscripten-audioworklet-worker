[emscripten-audioworklet-worker](https://dirkarnez.github.io/emscripten-audioworklet-worker)
============================================================================================
From [emscripten/test/webaudio/audioworklet_worker.c at main · emscripten-core/emscripten](https://github.com/emscripten-core/emscripten/blob/main/test/webaudio/audioworklet_worker.c)

### Tutorials
- [emscripten/test/test_browser.py at 8005679862f485b7e6755d489fc3a3e253fcbd3f · emscripten-core/emscripten](https://github.com/emscripten-core/emscripten/blob/8005679862f485b7e6755d489fc3a3e253fcbd3f/test/test_browser.py#L5086)

### Notes
- `Module.onRuntimeInitialized` is not allowed if `int main()` is used (because emscripten compiles it to [IIFE](https://developer.mozilla.org/zh-TW/docs/Glossary/IIFE))
