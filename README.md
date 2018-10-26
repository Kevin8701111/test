# 網頁爬蟲 — python3


## 環境需求

* virtualenv
* python3
* requests
* Beautiful soup
* scrapy
* docter
* splash

## 環境建置

###  Create Virtualenv 

#### 使用pip3下載Virtualenv
``` sh 
sudo apt-get install python3-pip
sudo pip3 install virtualenv
```

#### 建置Virtualenv 
``` sh 
virtualenv -p /usr/bin/python3 VMpython3 #machinename
```
#### 進入Virtualenv
``` sh 
source VMpython3/bin/activate
#看到Terminal上的user前面有（VMpython）就是已進入virtualenv
sudo apt-get remove python2.7
#如果在虛擬機仍看到python2, 強制scrapy使用python3
```
###  使用pip3下載所需工具
``` sh 
pip3 install requests
pip3 install beautifulsoup4
pip3 install scrapy

```
