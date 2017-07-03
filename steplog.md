#step log
##070117
- bazel build --config=mkl --copt="-march=broadwell" --copt="-DEIGEN_USE_VML" tensorflow/tools/quantization:quantize_graph
    