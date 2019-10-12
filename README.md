\# Codettes2019

**Image Classification**

Download the notebook:
wget <https://github.com/barbarahilsenbeck/Codettes2019>

Download data:
wget <https://s3.amazonaws.com/img-datasets/mnist.npz>

**Object Detection**

webpage: 
<https://pjreddie.com/darknet/yolo/>

git clone <https://github.com/pjreddie/darknet>

wget <https://pjreddie.com/media/files/yolov3-tiny.weights>

cd darknet

make

./darknet detect cfg/yolov3-tiny.cfg yolov3-tiny.weights data/dog.jpg
make
