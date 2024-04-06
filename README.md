## Nvidia documentation archives
* [DeepStream](https://docs.nvidia.com/metropolis/deepstream-archive.html)
* [TensorRT](https://docs.nvidia.com/deeplearning/tensorrt/archives/index.html)
* [CUDA](https://docs.nvidia.com/cuda/archive/)
* [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit-archive)
* [JetPack](https://developer.nvidia.com/embedded/jetpack-archive)
* [Jetson Linux](https://developer.nvidia.com/embedded/jetson-linux-archive)
## Learining TensorRT
### Usefull info?
  * github: [Nvidia/TensorRT](https://github.com/NVIDIA/TensorRT/releases)
  * [Operators Reference](https://docs.nvidia.com/deeplearning/tensorrt/archives/tensorrt-852/operators/index.html) (TRT 8.5.2) (Some version releases has this. Search thru archives, that are attached above)
    * [Operators](https://docs.nvidia.com/deeplearning/tensorrt/archives/tensorrt-852/operators/docs/index.html) (TRT 8.5.2)
    * [Layer fusion](https://docs.nvidia.com/deeplearning/tensorrt/archives/tensorrt-852/developer-guide/index.html#layer-fusion) (TRT 8.5.2)
  * TODO: [Explore TensorRT .engine execution graph? ](https://github.com/NVIDIA/TensorRT/tree/main/tools/experimental/trt-engine-explorer)
### Q
* How many tactics does TensorRT have?
  * TODO: Save .engine verbose logs to file -> regex parser to capture tactic title and ID, then save unique ones
    * [04/06/2024-16:21:09] [V] [TRT] Set Tactic Name: sm75_xmma_gemm_f16f16_f16f16_f16_tn_n_tilesize32x32x64_stage1_warpsize2x2x1_tensor16x8x8 Tactic: 0x00000000000202af numSplitK: 1 numBuffers: 0 numKernels: 1
    * https://regex101.com/
* How do tactics depend on memory pool size?
