#build commands

##cmd
bazel build 

##target
//tensorflow/tools/quantization:quantize_graph
//tensorflow/tools/graph_transforms:transform_graph
//tensorflow/tools/pip_package:build_pip_package
//tensorflow/examples/label_image:label_image
##extentions
###mkl
--config=mkl --copt="-march=broadwell" --copt="-DEIGEN_USE_VML"
--config=mkl --copt="-march=broadwell" --copt="-DEIGEN_USE_VML" -c opt 
##build zone
bazel build --config=mkl --copt="-march=broadwell" --copt="-DEIGEN_USE_VML" //tensorflow/examples/label_image:label_image