# Install DHT11 sensor

git clone https://github.com/adafruit/Adafruit_Python_DHT.git
cd Adafruit_Python_DHT
sudo python setup.py install

cd Adafruit_Python_DHT/examples

python AdafruitDHT.py 11 4

# JAVA Install
 

# 1.

curl -sL https://repos.influxdata.com/influxdb.key | sudo apt-key add -

#2. 

echo "deb https://repos.influxdata.com/debian stretch stable" | sudo tee /etc/apt/sources.list.d/influxdb.list 

#3.

sudo apt update
sudo apt install influxdb

#4.

sudo service influxdb start



# 데이터베이스 만들기

create database <데이터베이스 이름>



확인 : show databases



# Grafana Installation


## 1. Repository의 GPG key를 더하기


curl https://bintray.com/user/downloadSubjectPublicKey?username=bintray | sudo apt-key add -


## 2. Repository를 더하기


echo "deb https://dl.bintray.com/fg2it/deb stretch main" | sudo tee -a/atc/apt/sources.list.d/grafana.list


## 3. 프로그램 설치


sudo apt update
sudo apt install grafana


## 4. 프로그램 실행


sudo service grafana-server start

## influxdb import with python

sudo pip install influxdb

## gpio pin map

cd /tep
wget https://project-downloads.drogon.net/wiringpi-latest.deb
sudo dpkg -i wiringpi-latest.deb
```


pwd
/home/pi

pwd
/home/pi

cd /home/pi/
cd ~
git clone https://github.com/sonnonet/jjvision
```

### Git hub Use

 - Repository down load
 ```
 git clone https://github.com/doyeon0507/iotProject
 ```
 
 ## vim 편집기 사용법
 ```
 set nu       // Line numner
 set cindent  // C language indent
 set ts=4     // tab size 4
 set softtabtop=4
 set bg=dark
 set expandtab
 let python_version_2 = 1
 let python_highlight_all = 1
 filetype indent plugin on
 
 if has("syntax") // sysntax on
  systax on
  endif
  
```


#!/user/bin/python

import time
improt RPI.GPIO as GPIO 

GPIO.setmode(GPIO.BCM)
GPIO.setup(4, GPIO_IN)

def intterrupt_fired(channel):
 print("interrupt Fired")
 print(channel)
 
 GPIO.add_event_detect(4, GPIO.FALLING, callback=interrupt_firde)
 
 while(True);
  time.sleep(1)
  print("timer fired")
 
 is
 
 cd sttudy
 ls
 
 vim.pir.py
 python pir.py
 
 pip install
 
 
 pip 

cd 
Is
Is
cd ..
rm 
cd jjvision/

Is

README.md 

git add .
git commit -m pirsoftware

git push




