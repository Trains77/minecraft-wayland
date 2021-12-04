# minecraft-wayland
A patched version of GLFW that allows Minecraft Java to run natively on Wayland

Uses patches provided by https://github.com/Admicos/minecraft-wayland to allow Minecraft run natively on Wayland

This repo is meant to serve as an already patched and compiled version of libglfw

Add option -Dorg.lwjgl.glfw.libname=$PATH_TO_PATCHED_GLFW_FILE to Minecraft Arguments to force Minecraft to use patched version

# Compiling
Follow the instructions here: https://www.glfw.org/docs/latest/compile.html#compile_deps_wayland to compile project
