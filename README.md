# autoware_cuda

An [Autoware](https://github.com/autowarefoundation/autoware) repository that holds the shared CUDA and TensorRT base packages.

- It holds only packages that need CUDA to build.
- `autoware.repos` clones it to `src/core/cuda/autoware_cuda`.
- The `core-devel-cuda`, `core-cuda` and universe CUDA images hold it. The CPU-only images and `core-dependencies-cuda` do not.

The plan and the history of this repository are in [autowarefoundation/autoware#7340](https://github.com/autowarefoundation/autoware/issues/7340).
