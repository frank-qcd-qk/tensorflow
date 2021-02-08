# tensorflow for duckiebot DB21M
For original tensorflow readme, refer to (this)[https://github.com/duckietown/tensorflow/blob/daffy-2.3.2-arm64v8/README-tensorflow.md] link

## compile instruction

To compile, you will need the wheel builder from [dt-machine-learning-base-environment](https://github.com/duckietown/dt-machine-learning-base-environment/tree/daffy-staging/whl_builder) and run the command:

`/TFBuilder/tensorflow/third_party/aws# bazel build --config=cuda //tensorflow/tools/pip_package:build_pip_package --verbose_failures && ./bazel-bin/tensorflow/tools/pip_package/build_pip_package /tf_wheel/`
