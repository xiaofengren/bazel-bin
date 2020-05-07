# bazel-bin
Prebuilt aarch64 / arm64 bazel binaries.

built with the bazel-<ver>-dist.zip and  
```
EXTRA_BAZEL_ARGS="--host_javabase=@local_jdk//:jdk" bash ./compile.sh
```
For LSDK2004's Ubuntu Userland, use "bazel-1.2.1-aarch64-glibc-2.27" on target board. bazel need compatabile glibc and ubuntu18.04's glibc is 2.27.   
