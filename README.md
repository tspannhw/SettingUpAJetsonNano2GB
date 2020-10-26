# SettingUpAJetsonNano2GB
SettingUpAJetsonNano2GB

# Steps
 apt-get install fswebcam -y
 
mkdir /opt/demo/images
mkdir /opt/demo/logs

scp minifi-0.6.0.1.2.0.0-70-bin.zip tspann@192.168.1.169:/opt/demo/ 
scp nifi-minifi-cpp-0.6.0-bin.tar.gz tspann@192.168.1.170:/opt/demo/

unzip minifi*.zip
tar -xvf nifi*.gz

git clone https://github.com/tspannhw/minifi-jetson-nano
 
chmod -R 777 /opt/demo
 
