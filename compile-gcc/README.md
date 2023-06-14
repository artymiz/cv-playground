# Compiling opencv with GCC and CMake

OpenCV tutorial for an easy image display program compiled using CMake.

[link](https://docs.opencv.org/4.x/db/df5/tutorial_linux_gcc_cmake.html)

### Usage

run compiled binary with an image location as the argument

```bash
./DisplayImage.cpp imgDirectory/sampleImage.jpg
```

### Requirements

Make sure openCV is install prior to building following this [guide](https://docs.opencv.org/4.x/d7/d9f/tutorial_linux_install.html)

### Build

Build with standard cmake commands

```bash
mkdir -p build && cd build
cmake ..
make
```

