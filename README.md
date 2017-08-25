# PowerAI frameworks testing using nvidia/cuda-ppc64le image

Build image command:
```
docker build -t nvidia-powerai .
```
Run container command:
```
nvidia-docker run --rm -it nvidia-powerai
```
Caffe test command (run in the container):
```
source /opt/DL/caffe-ibm/bin/caffe-activate
/opt/DL/caffe-ibm/bin/caffe-test
```
Tensorflow test command (run in the container):
```
source /opt/DL/tensorflow/bin/tensorflow-activate
/opt/DL/tensorflow/bin/tensorflow-test
```
