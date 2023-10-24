# Rippling effect on GPU (Nvidia CUDA).
Creating Rippling effect using OpenGL and Nvidia GPU. Based on "Cuda by example book".

## Setup
1. Install latest nvidia c++ compiler(i.e nvcc).
2. Build command for the program, it is present in `ripple_effect` folder.
    ```
    nvcc ./ripple_effect/main.cu -o ripple -lglut -lGLU -lGL
    ```
3. To render graphical image.
    ```
    ./ripple_effect
    ```