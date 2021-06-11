# flutter-engine-binaries
flutter engine embedder binaries built by android ndk toolchain.

# flutter-engine-version
build from flutter 2.2.1 stable
engine commit id :0fdb562ac8068ce3dda6b69aca3f355f4d1d2718

# How to build flutter engine by ndk
1. follow flutter engine build offical guide :(https://github.com/flutter/flutter/wiki/Compiling-the-engine)
2. switch flutter engine 2.2.1 stable commit id : (0fdb562ac8068ce3dda6b69aca3f355f4d1d2718)
3. apply engine-build-by-ndk.diff
```
git apply path/to/engine-build-by-ndk.diff
```
4. the flutter engine build gn args is:
```
    flutter/tools/gn 
    --android 
    --runtime-mode = debug/release/profile
    --android-cpu = arm64
```
