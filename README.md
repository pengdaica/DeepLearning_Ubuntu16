# How to setup system for deep learning with fresh new Ubuntu16
For computer vision packages, some general dependencies are
```
sudo apt-get update
sudo apt-get upgrade

sudo apt-get install build-essential cmake pkg-config
sudo apt-get install libjpeg8-dev libtiff5-dev libjasper-dev libpng12-dev
sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
sudo apt-get install libxvidcore-dev libx264-dev

sudo apt-get install libgtk-3-dev libatlas-base-dev gfortran python2.7-dev python3.5-dev
```
## setup python

```
sudo apt-get install python-pip
```

Setup python virtual environment
```
sudo pip install virtualenv virtualenvwrapper
# virtualenv and virtualenvwrapper
export WORKON_HOME=$HOME/.virtualenvs
source /usr/local/bin/virtualenvwrapper.sh
```
You can also us Anaconda. It's quite handy. Personally, I prefer 'light weight' one.
# OpengCV

# Dlib

# Caffe

# References
[1] https://www.pyimagesearch.com/2016/10/24/ubuntu-16-04-how-to-install-opencv/   
[2] http://iamaaditya.github.io/2016/01/Deep-Learning-software-installation-guide-on-fresh-Ubuntu/   


