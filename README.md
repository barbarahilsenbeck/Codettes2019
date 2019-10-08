# Codettes2019


**Object Detection**

Download data:
https://s3.amazonaws.com/img-datasets/mnist.npz

webpage: 
https://pjreddie.com/darknet/yolo/

git clone https://github.com/pjreddie/darknet

wget https://pjreddie.com/media/files/yolov3-tiny.weights
cd darknet

./darknet detect cfg/yolov3-tiny.cfg yolov3-tiny.weights data/dog.jpg
make
