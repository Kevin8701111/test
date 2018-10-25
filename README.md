# 網頁爬蟲 — python3


環境需求
---
* virtualenv
* python3
* request
* Beautiful soup
* scrapy
* docter
* splash

環境建置
---
###  Create Virtualenv 

``` sh 
sudo apt-get install python3-pip
sudo pip3 install virtualenv
```
``` sh 
virtualenv VMpython3 #machinename
virtualenv -p /usr/bin/python3 VMpython3
```
``` sh 
source VMpython3/bin/activate
#看到Terminal上的user前面有（VMpython）就是已進入virtualenv
sudo apt-get remove python2.7
#強制scrapy使用python3
```
###  
``` sh 
pip3 install requests
pip3 install beautifulsoup4
pip3 install scrapy

```
