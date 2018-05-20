# -ubantu-
- **获得root权限**  
su 按enter
如果认证失败，可以sudo passwd root。
- **命令安装python3**  
sudo apt-get install python3
- **安装idle**  
sudo apt-get install idle3  
- **修改默认python版本**。
sudo update-alternatives --install /usr/bin/python python /usr/bin/python2 100  
sudo update-alternatives --install /usr/bin/python python /usr/bin/python3 150  
sudo update-alternatives --config python 
