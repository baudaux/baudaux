:bear: **exaequOS** is (or will be 😄) a Unix-like operating system running on every (up-to-date) web browser. Developpers will able to develop applications for it (in C, C++, Lua, Basic, ...) and to share them easily through the platform. Anybody will be able to execute them with no installation.

**EXA Kernel**: EXA is the kernel of exeaquOS. It is designed as a microkernel architecture (resource manager, drivers and user processes) adapted to a web browser environment.

**emscripten-exa**: A fork ok Emscripten is used for compiling C/C++ source code to WebAssembly in order to have the best possible performances. As Emscripten is not designed for a multi-process environment, a rework for handling the system calls is needed.
