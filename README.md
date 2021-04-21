# TrainCustomModel - Introduction
This repository will explain you the way to train your custom object detection model using tensorflow via google colab (FREE GPU). This tutorial is a combination of several tutorial below:

#### 1. [How to train custom object detection model using Google Colab (Free GPU) Part 1](https://www.youtube.com/watch?v=f2ccs2xziLk)
#### 2. [How to train custom object detection model using Google Colab (Free GPU) Part 2](https://www.youtube.com/watch?v=5qQB8dZRgXQ)
#### 3. [How to train custom object detection model using Google Colab (Free GPU) Part 3](https://www.youtube.com/watch?v=SMis3UjTIBY)
#### 4. [How to Train a Custom Model for Object Detection (Local and Google Colab!)](https://www.youtube.com/watch?v=_gGI91BmIdk)


<br><center>![Pose Estimator Analyzer](results/result.gif "Result of Custom Training")</center></br>

## LabelImg Setup

### Windows
1. You can download labelImg [here](https://github.com/tzutalin/labelImg/files/2638199/windows_v1.8.1.zip)
2. Change `predefined_classes.txt` inside `data` with your object target name. Here is the example that i use:
```
goalpost
ball
x_line
t_line
l_line
eros
```
### Linux
1. Open your terminal
2. Type these following commands:
```bash
sudo apt-get update
sudo apt-get install python3 python3-pip pyqt5-dev-tools git
git clone https://github.com/tzutalin/labelImg.git
cd labelImg
pip3 install -r requirements/requirements-linux-python3.txt
make qt5py3
```

3.  Change `predefined_classes.txt` inside `data` with your object target name. Here is the example that i use:
```
goalpost
ball
x_line
t_line
l_line
eros
```

4.  To run labelImg, you can type `python3 labelImg.py` in your terminal inside labelImg folder