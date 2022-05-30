## About
Rendering engine prototype made with `Vulkan`. Code is written using [a simpler C++ coding style](https://gist.github.com/bkaradzic/2e39896bc7d8c34e042b). Project requires `C++11` standard and a `x64` system. Currently the code is tested only on `Windows`, using `MSVC` (Visual Studio) and `MINGW` (Visual Studio Code) compilers, but the `Linux` is not completely supported yet.

![Demo](https://github.com/milkru/data_resources/blob/main/proto_vk/kitten.png)

## Features
* Single mesh rendering
* In-flight frames
* CPU and GPU profiling

## Installation
This project uses [CMake](https://cmake.org/download/) as a build tool. Since the project is built using `Vulkan`, the latest [Vulkan SDK](https://vulkan.lunarg.com) should be installed.

## License
Distributed under the MIT License. See `LICENSE` for more information.
