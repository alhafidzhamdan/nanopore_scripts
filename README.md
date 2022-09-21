# Walkthrough on setting up ONT system

1) Get a GPU enabled PC- our system is NVIDIA RTX 3080, run with Intel Core i9-12900K, 16 Cores, 24 Threads, 32Gb DDR5 SDRAM
2) Check NVIDIA driver is installed by typing "nvidia-smi"
3) Install CUDA from https://developer.nvidia.com/cuda-downloads?target_os=Windows&target_arch=x86_64&target_version=11&target_type=exe_local
4) Check for CUDA installation by typing "nvcc --version"
5) Install minKNOW 
6) Install GPU-enabled Guppy, make sure using the same Guppy version as the one used by minKNOW (https://community.nanoporetech.com/docs/prepare/library_prep_protocols/experiment-companion-minknow/v/mke_1013_v1_revcl_11apr2016/installing-a-gpu-version-of-guppy-with-minknow-for-minion-on-windows)
7) Change configuration for minKNOW to enable GPU base calling
