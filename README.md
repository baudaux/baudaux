### Hi everybody 👋

:bear: EXtended mAchine is (or will be 😄) a GNU/EXA distribution that will allow you to run your desktop environment in any up-to-date web browser. The difference with other webOS is that EXtened mAchine will be able to run any application using POSIX interface.

**GNU/EXA distribution**
The purpose is to be able to port any tool and application belonging to the GNU ecosystem: Bash, vi, emacs, ... It will be a universal application store that will contain applications runnable in every web browser.

**EXA Operating System**
EXA is the Operating System of EXtended mAchine. It is designed as a microkernel architecture (resource manager, drivers and user processes).

**Compiling C to WebAssembly**
A fork ok Emscripten is used for compiling C source code to WebAssembly in order to have the best possible performances. As Emscripten is not designed for a multi-process environment, a rework for handling the system calls is needed.
