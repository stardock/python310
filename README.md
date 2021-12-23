# python310
Build Python3.10

Attension: starting python3.10, it needs the minimum version of openssl 1.1.1  

prepare the ubuntu 18.04  
check openssl version  

install dependecies:
```  
apt install wget build-essential checkinstall -y
apt install libreadline-gplv2-dev libncursesw5-dev libssl-dev -y
apt install libsqlite3-dev tk-dev libgdbm-dev libc6-dev libbz2-dev libffi-dev zlib1g-dev -y
```  

```  
wget https://www.python.org/ftp/python/3.10.0/Python-3.10.0.tgz
tar xvf Python-3.10.0.tgz
cd Python-3.10.0
./configure --enable-optimizations
```  



`make altinstall`


reference:  
https://techviewleo.com/how-to-install-python-on-centos-linux/  
https://cloud.tencent.com/developer/article/1846039  
