# CUDA-Accelerated Sobel Edge Detection

## Project Overview

This project explores Sobel edge detection using CUDA for parallel image processing. The goal is to process image pixels in parallel on the GPU and study how CUDA can be applied to an image-processing workload.

> **Important:** Replace the placeholder sections below with details from your own implementation before submitting.

## Features

- CUDA-based Sobel edge detection
- Parallel processing of image pixels
- CPU-to-GPU data transfer
- GPU kernel execution
- Boundary checking for neighboring pixels
- Output of the processed edge-detected image

## Requirements

- NVIDIA GPU with CUDA support
- CUDA Toolkit
- C/C++ compiler
- [Add any image-processing library used by your project]

## Project Structure

```text
cuda-sobel-edge-detection/
├── README.md
├── [your_cuda_source_file].cu
├── [your_header_file].h
├── [your_build_file]
└── [your_input_files]
```

Update this structure so that it exactly matches your repository.

## Build

Add the exact build command used for your project here.

Example:

```bash
nvcc [your_source_file].cu -o sobel
```

## Usage

Add the exact command-line syntax supported by your program here.

Example:

```bash
./sobel <input_image> <output_image>
```

### Arguments

- `input_image` — path to the input image
- `output_image` — path where the processed image is saved

Update these arguments to match your actual program.

## How It Works

1. The input image is loaded.
2. Image data is transferred from CPU memory to GPU memory.
3. CUDA threads process pixels in parallel.
4. The Sobel operation calculates horizontal and vertical gradients.
5. Boundary conditions are checked when accessing neighboring pixels.
6. The processed result is copied back to the CPU.
7. The edge-detected image is saved.

## Results

Add your actual execution results here.

Include:
- Input image
- Output image
- Image dimensions
- Execution time
- CPU/GPU comparison, if implemented

Do not add results that were not actually produced by your program.

## What I Learned

Write a short description in your own words about what you learned while implementing the project, such as CUDA kernel execution, thread organization, GPU memory management, and image-processing parallelism.

## References

Add the references you actually used while developing the project.
