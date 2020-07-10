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
sudo apt install influxdb:w

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


import RPi.GPIO as GPIO
import time

channel = 4

GPIO


# --------------------------------------------------------------------------------------------------------------------
pi@raspberrypi:~ $ influxdb
bash: influxdb: command not found
pi@raspberrypi:~ $ influx
Connected to http://localhost:8086 version 1.8.0
InfluxDB shell version: 1.8.0
> create database co2
> exit
pi@raspberrypi:~ $ sudo service grafana-server start
pi@raspberrypi:~ $ pip3 install python-telegram-bot--upgrade
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Collecting python-telegram-bot--upgrade
Could not install packages due to an EnvironmentError: 404 Client Error: Not Found for url: https://pypi.org/simple/python-telegram-bot-upgrade/

pi@raspberrypi:~ $ pip3 install python-telegram-bot --upgrade
Looking in indexes: https://pypi.org/simple, https://www.piwheels.org/simple
Collecting python-telegram-bot
  Downloading https://files.pythonhosted.org/packages/a6/2d/c72fc9a28144277f6170f2fcbfd3bd9427943497522b2689846596eb86cf/python_telegram_bot-12.8-py2.py3-none-any.whl (375kB)
    100% |################################| 378kB 902kB/s 
Requirement already satisfied, skipping upgrade: tornado>=5.1 in /usr/lib/python3/dist-packages (from python-telegram-bot) (5.1.1)
Requirement already satisfied, skipping upgrade: certifi in /usr/lib/python3/dist-packages (from python-telegram-bot) (2018.8.24)
Requirement already satisfied, skipping upgrade: cryptography in /usr/lib/python3/dist-packages (from python-telegram-bot) (2.6.1)
Collecting decorator>=4.4.0 (from python-telegram-bot)
  Downloading https://files.pythonhosted.org/packages/ed/1b/72a1821152d07cf1d8b6fce298aeb06a7eb90f4d6d41acec9861e7cc6df0/decorator-4.4.2-py2.py3-none-any.whl
Installing collected packages: decorator, python-telegram-bot
Successfully installed decorator-4.4.2 python-telegram-bot-12.8
pi@raspberrypi:~ $ mv python-telegram-bot/ ../python-telegram-bot/
mv: cannot stat 'python-telegram-bot/': 그런 파일이나 디렉터리가 없습니다
pi@raspberrypi:~ $ ls
Bookshelf  Documents  Music     Public     Videos  iotProject  work
Desktop    Downloads  Pictures  Templates  co2.py  pir.py
pi@raspberrypi:~ $ cd python-telegram-bot/
bash: cd: python-telegram-bot/: 그런 파일이나 디렉터리가 없습니다
pi@raspberrypi:~ $ git clone https://github/com/python-telegram-bot/python-telegram-bot--recursive
'python-telegram-bot--recursive'에 복제합니다...
fatal: unable to access 'https://github/com/python-telegram-bot/python-telegram-bot--recursive/': Could not resolve host: github
pi@raspberrypi:~ $ mv python-telegram-bot/ ../python-telegram-bot/
mv: cannot stat 'python-telegram-bot/': 그런 파일이나 디렉터리가 없습니다
pi@raspberrypi:~ $ cd python-telegram-bot/
bash: cd: python-telegram-bot/: 그런 파일이나 디렉터리가 없습니다
pi@raspberrypi:~ $ git clone https://github/com/python-telegram-bot/python-telegram-bot --recursive
'python-telegram-bot'에 복제합니다...
fatal: unable to access 'https://github/com/python-telegram-bot/python-telegram-bot/': Could not resolve host: github
pi@raspberrypi:~ $ git clone https://github.com/python-telegram-bot/python-telegram-bot --recursive
'python-telegram-bot'에 복제합니다...
remote: Enumerating objects: 17, done.
remote: Counting objects: 100% (17/17), done.
remote: Compressing objects: 100% (16/16), done.
remote: Total 15876 (delta 7), reused 4 (delta 1), pack-reused 15859
오브젝트를 받는 중: 100% (15876/15876), 6.21 MiB | 3.81 MiB/s, 완료.
델타를 알아내는 중: 100% (12519/12519), 완료.
'telegram/vendor/ptb_urllib3' 경로에 대해 'telegram/vendor/urllib3' (https://github.com/python-telegram-bot/urllib3.git) 하위 모듈 등록
'/home/pi/python-telegram-bot/telegram/vendor/ptb_urllib3'에 복제합니다...
remote: Enumerating objects: 12388, done.        
remote: Total 12388 (delta 0), reused 0 (delta 0), pack-reused 12388        
오브젝트를 받는 중: 100% (12388/12388), 3.07 MiB | 2.15 MiB/s, 완료.
델타를 알아내는 중: 100% (8699/8699), 완료.
하위 모듈 경로 'telegram/vendor/ptb_urllib3': '1954df03958b164483282330b3a58092c070bc7a' 체크아웃
pi@raspberrypi:~ $ ls
Bookshelf  Downloads  Public     co2.py      python-telegram-bot
Desktop    Music      Templates  iotProject  work
Documents  Pictures   Videos     pir.py
pi@raspberrypi:~ $ cd python-telegram-bot/examples/
pi@raspberrypi:~/python-telegram-bot/examples $ ls
LICENSE.txt           echobot.py                 nestedconversationbot.py
README.md             echobot2.py                passportbot.html
conversationbot.png   errorhandlerbot.py         passportbot.py
conversationbot.py    inlinebot.py               paymentbot.py
conversationbot2.png  inlinekeyboard.py          persistentconversationbot.py
conversationbot2.py   inlinekeyboard2.py         pollbot.py
deeplinking.py        nestedconversationbot.png  timerbot.py
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $  python3-telegram-bot/
bash: python3-telegram-bot/: 그런 파일이나 디렉터리가 없습니다
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 telegram bot
python3: can't open file 'telegram': [Errno 2] No such file or directory
pi@raspberrypi:~/python-telegram-bot/examples $ python timerbot.py 
Traceback (most recent call last):
  File "timerbot.py", line 23, in <module>
    from telegram.ext import Updater, CommandHandler
ImportError: No module named telegram.ext
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python timerbot.py 
Traceback (most recent call last):
  File "timerbot.py", line 23, in <module>
    from telegram.ext import Updater, CommandHandler
ImportError: No module named telegram.ext
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ timerbot.py
bash: timerbot.py: command not found
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
Traceback (most recent call last):
  File "timerbot.py", line 109, in <module>
    main()
  File "timerbot.py", line 100, in main
    updater.start_polling()
  File "/home/pi/.local/lib/python3.7/site-packages/telegram/ext/updater.py", line 259, in start_polling
    self.job_queue.start()
  File "/home/pi/.local/lib/python3.7/site-packages/telegram/ext/jobqueue.py", line 446, in start
    name="Bot:{}:job_queue".format(self._dispatcher.bot.id))
  File "/home/pi/.local/lib/python3.7/site-packages/telegram/bot.py", line 51, in decorator
    self.get_me()
  File "<decorator-gen-1>", line 2, in get_me
  File "/home/pi/.local/lib/python3.7/site-packages/telegram/bot.py", line 67, in decorator
    result = func(*args, **kwargs)
  File "/home/pi/.local/lib/python3.7/site-packages/telegram/bot.py", line 289, in get_me
    result = self._request.get(url, timeout=timeout)
  File "/home/pi/.local/lib/python3.7/site-packages/telegram/utils/request.py", line 276, in get
    result = self._request_wrapper('GET', url, **urlopen_kwargs)
  File "/home/pi/.local/lib/python3.7/site-packages/telegram/utils/request.py", line 242, in _request_wrapper
    raise Unauthorized(message)
telegram.error.Unauthorized: Unauthorized
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
^C2020-07-10 15:45:16,556 - telegram.ext.updater - INFO - Received signal 2 (SIGINT), stopping...
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
^C2020-07-10 15:47:14,772 - telegram.ext.updater - INFO - Received signal 2 (SIGINT), stopping...
pi@raspberrypi:~/python-telegram-bot/examples $ ^C
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
^C2020-07-10 15:56:10,770 - telegram.ext.updater - INFO - Received signal 2 (SIGINT), stopping...
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ 
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 36
    try
      ^
SyntaxError: invalid syntax
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 36
    try:
      ^
IndentationError: expected an indented block
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 44
    except Exception as e:
         ^
SyntaxError: invalid syntax
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 44
    except Exception as e:
         ^
SyntaxError: invalid syntax
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 44
    except Exception as e:
         ^
SyntaxError: invalid syntax
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 113
    updater.start_polling()
    ^
IndentationError: unexpected indent
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 110
    dp_handler(CommandHandler("co2",co2))
                                        ^
TabError: inconsistent use of tabs and spaces in indentation
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 113
    updater.start_polling()
    ^
IndentationError: unexpected indent
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 109
    dp.adp.add_handler(CommandHandler("unset", unset, pass_chat_data=True))
    ^
IndentationError: unexpected indent
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 113
    updater.start_polling()
    ^
IndentationError: unexpected indent
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 113
    updater.start_polling()
    ^
IndentationError: unexpected indent
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 110
    dp.adp.add_handler(CommandHandler("co2",co2))
                                                ^
TabError: inconsistent use of tabs and spaces in indentation
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 110
    dp.add_handler(CommandHandler("co2",co2))
                                            ^
TabError: inconsistent use of tabs and spaces in indentation
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 110
    dp.add_handler(CommandHandler("co2",co2))
                                            ^
TabError: inconsistent use of tabs and spaces in indentation
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
  File "timerbot.py", line 113
    updater.start_polling(
    ^
IndentationError: unexpected indent
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
Traceback (most recent call last):
  File "timerbot.py", line 32, in <module>
    device = srial.Serial('/dev/ttyAMA0', 38400, timeout = 5)
NameError: name 'srial' is not defined
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
Traceback (most recent call last):
  File "timerbot.py", line 121, in <module>
    main()
  File "timerbot.py", line 109, in main
    dp.adp.add_handler(CommandHandler("unset", unset, pass_chat_data=True))
AttributeError: 'Dispatcher' object has no attribute 'adp'
pi@raspberrypi:~/python-telegram-bot/examples $ vim timerbot.py 
pi@raspberrypi:~/python-telegram-bot/examples $ python3 timerbot.py 
^C2020-07-10 16:44:28,986 - telegram.ext.updater - INFO - Received signal 2 (SIGINT), stopping...
^C2020-07-10 16:44:37,511 - telegram.ext.updater - WARNING - Exiting immediately!
pi@raspberrypi:~/python-telegram-bot/examples $ 


import logging
 22 
 23 from telegram.ext import Updater, CommandHandler
 24 
 ## import sys, serial, time

 ## device = serial.Serial('/dev/ttyAMA0', 38400, timeout = 5)
 33 # Define a few command handlers. These usually take the two arguments update and
 34 # context. Error handlers also receive the raised TelegramError object in error.
 35 def co2(update, context):
 ## try:
 37  ```             rcBuf = bytearray()
 38                 device.reset_input_buffer()
 39                 rcvBuf = device.read_until(size=12)
 40                 temp = str(rcvBuf)
 41                 a = temp.find('m')
 42                 t = temp[0:a+1]
 43                 update.message.reply_text(t)
 44         except Exception as e:
 45                 
 print("Exception read") + str(e)
 ```
 ```
 
 46 def start(update, context):
 47     update.message.reply_text('Hi! Do yeon!!!!!! /set <seconds> to set a timer')
 48 



 on different commands - answer in Telegram
103     dp.add_handler(CommandHandler("start", start))
104     dp.add_handler(CommandHandler("help", start))
105     dp.add_handler(CommandHandler("set", set_timer,
106                                   pass_args=True,
107                                   pass_job_queue=True,
108                                   pass_chat_data=True))
109     dp.add_handler(CommandHandler("unset", unset, pass_chat_data=True))

## dp.add_handler(CommandHandler("co2",co2))

111 
112     # Start the Bot
113     updater.start_polling( )




