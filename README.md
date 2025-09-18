# TIC-80 custom build for *o moku e mun*

## Changes

- Turn off integer scale by default in html export (`defined(__EMSCRIPTEN__)` → `#define INTEGER_SCALE_DEFAULT false` in src/studio/config.c)
- Replace icon for Linux executable: build/linux/tic80.png
- Replace icon for Windows executable: build/windows/icon.ico
- Replace icon for 3ds executable: build/n3ds/icon.ico