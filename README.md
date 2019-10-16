<h1>Codettes2019</h1>


**Image Classification with LeNet5**

Download the notebook:
<https://github.com/barbarahilsenbeck/Codettes2019>

Download data:

cd Codettes2019

wget <https://s3.amazonaws.com/img-datasets/mnist.npz>


**Object Detection with YOLO**

Check out the video in the webpage: 
<https://pjreddie.com/darknet/yolo/>

git clone <https://github.com/pjreddie/darknet>

cd darknet

make

wget <https://pjreddie.com/media/files/yolov3-tiny.weights>

./darknet detect cfg/yolov3-tiny.cfg yolov3-tiny.weights data/dog.jpg
