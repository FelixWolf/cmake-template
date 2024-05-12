# Cross compile CMake Template
This is the CMake template I use for my projects going forward.


# How to use it
1. `mkdir build`
2. `cd build`
3. `cmake ..` optionally specifying cross compile target using `-DTARGET_*=ON`


# Supported targets
## Native
1. Linux
2. Windows


## Cross compile
1. `TARGET_EMSCRIPTEN` - https://emscripten.org
2. `TARGET_PSVITA` - https://vitasdk.org
3. `TARGET_N3DS` - https://libctru.devkitpro.org
4. `TARGET_MINGW64` - https://www.mingw-w64.org
5. `TARGET_MINGW32` - https://www.mingw-w64.org


# Planned targets
1. Android
2. Mac OSX
3. iOS


# License
The template is public domain, feel free to use it for whatever you want.