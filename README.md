# GFx

## Requirements (all free)

- [Visual Studio Community](https://visualstudio.microsoft.com/vs/community/) 2026 with the **Desktop development with C++** workload (provides the MSVC compiler)
- [CMake](https://cmake.org/) 3.25+

## Build and run

```bash
cmake --preset default
cmake --build --preset debug
./build/Debug/GFx.exe
```

For an optimised build use `cmake --build --preset release` and run `./build/Release/GFx.exe`.

## License

GFx is licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE.md).
You may use, modify and share it for noncommercial purposes only. Commercial use,
including in software that is sold, requires a separate license from the author.

Required Notice: Copyright (c) 2026 Outlands
