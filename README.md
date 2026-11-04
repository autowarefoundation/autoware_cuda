# autoware_cuda

An [Autoware](https://github.com/autowarefoundation/autoware) repository that holds the shared CUDA and TensorRT base packages.

- It holds only packages that need CUDA to build.
- `autoware.repos` clones it to `src/core/cuda/autoware_cuda`.
- The `core-devel-cuda` and `core-cuda` images hold it, and so do the universe CUDA images on top of them. The CPU-only core images and `core-dependencies-cuda` do not.

The plan and the history of this repository are in [autowarefoundation/autoware#7340](https://github.com/autowarefoundation/autoware/issues/7340).
