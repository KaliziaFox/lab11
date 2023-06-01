# Лабораторная работа №11

$ sudo snap install ngrok
$ ngrok config add-authtoken 2QbV6DFVo91K6BPmRqaeYYgO6U5_59bq5mXw6sdV7iGhL99MT
$ sudo apt-get install openssh-server
$ sudo systemctl start ssh
$ sudo systemctl status ssh

открываем новое окно терминала

$ python3 -m http.server - распакова модуля http.server
![image](https://github.com/KaliziaFox/lab11/assets/112780370/06526132-b262-4a66-acec-d4e9a90b0598)

$ nano index.html

$ ngrok tcp 22 - запускаю TCP туннель
![image](https://github.com/KaliziaFox/lab11/assets/112780370/90f4b87f-8484-4fc0-a371-219c851413f9)

ssh 6.tcp.eu.ngrok.io -p 15142

