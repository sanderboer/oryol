# Oryol
 
A small, portable and extensible 3D coding framework written in C++:

- simple [Orthodox C++](https://gist.github.com/bkaradzic/2e39896bc7d8c34e042b) coding style and APIs
- extensible through external code modules living in git repositories
- runs on OSX, Linux (incl RaspberryPi), Windows, iOS, Android, emscripten, PNaCl from the same C++ source
- renders through GL, GLES2, WebGL, Metal, D3D11, D3D12 and
soon-ish Vulkan from the same C++ and shader source
- produces small executables (e.g. emscripten WebGL demos starting at around 100 Kbytes)
- async data loading from web or disc 

### Build Status:

|Platform|Build Status|
|--------|------|
|OSX + Linux (OpenGL)|[![Build Status](https://travis-ci.org/floooh/oryol.svg?branch=master)](https://travis-ci.org/floooh/oryol)|
|Windows (OpenGL + D3D11)|[![Build status](https://ci.appveyor.com/api/projects/status/hn5sup2y532h64jg/branch/master?svg=true)](https://ci.appveyor.com/project/floooh/oryol/branch/master)|

### How to Build (Quick'n'Dirty):

You need: cmake, python and your platform's default C/C++ development environment.

```bash
> mkdir projects
> cd projects
> git clone https://github.com/floooh/oryol
> cd oryol
> ./fips build
> ./fips run Triangle
```

In case of problems or for more detailed build info (e.g. how to work
with IDEs) see here: [How to Build](doc/BUILD.md)

### Getting Started:

* [How to Build](doc/BUILD.md)
* [What's New](doc/NEWS.md)
* [Design Manifesto](doc/DESIGN-MANIFESTO.md)
* [10,000ft View](doc/OVERVIEW.md)
* [Core Module](code/Modules/Core/README.md)
* [IO Module](code/Modules/IO/README.md)
* [Gfx Module](code/Modules/Gfx/README.md)

### Live Demos:

- Oryol Core Samples: http://floooh.github.io/oryol/
- Oryol Extension Samples: http://floooh.github.io/oryol-samples/
- KC85 emulator: http://floooh.github.io/virtualkc/

### Extension Modules:

- Dear Imgui integration: https://github.com/floooh/oryol-imgui
- TurboBadger UI integration: https://github.com/floooh/oryol-tbui
- OpenAL based sound module: https://github.com/floooh/oryol-sound
- SoLoud portable audio library: https://github.com/floooh/fips-soloud
- ...more coming soon!

### Standalone App Demo:

A simple standalone app using Oryol: https://github.com/floooh/oryol-test-app

### Videos 

Please note that these videos use older versions of the Gfx module, details
have changed (and will continue to change at least until the Vulkan and DX12
renderer backends have been implemented).

- Coding a triangle from scratch [OSX](http://www.youtube.com/watch?v=B5R0uE5IMZs), [Windows](http://www.youtube.com/watch?v=fcmOhvVd80o)
- [Building a standalone app](https://www.youtube.com/watch?v=z8nwrGh2Zsc)
- [Compiling and debugging in QtCreator and CLion](https://www.youtube.com/watch?v=Sp5TywYeNzE)

#### Enjoy! ####




