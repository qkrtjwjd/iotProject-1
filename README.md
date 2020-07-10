# Install DHT11 sensor

git clone https://github.com/adafruit/Adafruit_Python_DHT.git
cd Adafruit_Python_DHT
sudo python setup.py install

cd Adafruit_Python_DHT/examples

python AdafruitDHT.py 11 4

# JAVA Install
 

#1.

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
git
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


## 
sudo apt raspi-config
SNC Viewer
sncserver

cd /
ls
cd ~
cd - 
cd /home/pi


cp pir.py Documents/
cp pir.py Documents/pir.py
cd Documents/
ls
>>pir.py

pwd
/home/pi/Documents

cd ..
pwd
/home/pi

# bluetooth disable
sudo systenctk disable hcuiart



# !/usr/bin/python
```
import sys, serial, time

comm = 'dev/ttyAMA0'
bauadrate = 38400

device = serial.Serial(comm, baudrate, timeout = 5)
print(device)

while True :
 try:
  rcvBuf = bytearray()
  device.reset_input_bufer()
  rcvBuf = device.read_until(size=12)

  print rcvBuf
  temp = rcvBuf.find('p')
  a = rcvBuf[2:temp]
  b = int(a)
  print b
  except Exception as e:
   print("Exception read") + str(e)
   time.sleep(5)


```
# grafana
```
sudo service grafana-server start

```
# telegram install
```
pip3 install python-telegram-bot --upgrade
```

git clone https://github.com/python-telegram-bot/python-telegram-bot --recursive

ls
cd python-telegram-bot/examples/

ls
vim timerbot.py

>> 85 : 1346081175:AAHryYn6BrTHQ_UOabcVyKqOtXmh_KCHQdM

python3 timerbot.py 
vim timerbot.py

>> 35 : Hi Do yeon!!!!!!!!








