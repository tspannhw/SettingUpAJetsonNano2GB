# SettingUpAJetsonNano2GB

SettingUpAJetsonNano2GB

# Steps
## apt-get install fswebcam -y
##  
## mkdir /opt/demo/images
## mkdir /opt/demo/logs
## 
## scp minifi-0.6.0.1.2.0.0-70-bin.zip tspann@192.168.1.169:/opt/demo/ 
## scp nifi-minifi-cpp-0.6.0-bin.tar.gz tspann@192.168.1.170:/opt/demo/
## 
## unzip minifi*.zip
## tar -xvf nifi*.gz
## 
## git clone https://github.com/tspannhw/minifi-jetson-nano
## sudo apt-get update -y
## sudo apt-get install git cmake libpython3-dev python3-numpy -y
## git clone --recursive https://github.com/dusty-nv/jetson-inference
## cd jetson-inference
## mkdir build
## cd build
## cmake ../
## make -j$(nproc)
## sudo make install
## sudo ldconfig
## 
## chmod -R 777 /opt/demo
## 
git clone https://github.com/tspannhw/iot-device-install


# optional 
sudo apt-get install libatlas-base-dev gfortran -y
sudo apt-get install libhdf5-serial-dev hdf5-tools -y

sudo apt-get install python3-dev -y
sudo apt-get install libcv-dev libopencv-dev -y
sudo apt-get install fswebcam -y
sudo apt-get install libv4l-dev -y
sudo apt-get install python-opencv -y
pip3 install psutil
pip2 install psutil
pip3.6 install easydict -U
pip3.6 install scikit-learn -U
pip3.6 install opencv-python -U --user
pip3.6 install numpy -U
pip3.6 install mxnet -U
pip3.6 install mxnet-mkl -U
pip3.6 install gluoncv --upgrade
sudo apt-get install libhdf5-serial-dev hdf5-tools libhdf5-dev zlib1g-dev zip libjpeg8-dev -y
# sudo apt-get install python3-pip
sudo pip3 install -U pip
sudo pip3 install --pre --extra-index-url https://developer.download.nvidia.com/compute/redist/jp/v42 tensorflow-gpu
# sudo nvpmodel -q --verbose
pip3 install keras
# tegrastats
pip3 install -U jetson-stats
pip3 install -U psutil
sudo apt-get install openjdk-8-jdk -y
