# How to install RabbitMQ

## Steps:

1. First you need to stop one service that is starting from "Avecto Defendpoint ...." for that follow from 2nd step

   <img src="https://github.com/RMohit927/Tips-Tricks/blob/main/RabbitMQ/first.jpg" height="300">

2. give Admin credentials then ok
3. Then create Run New Task

   <img src="https://github.com/RMohit927/Tips-Tricks/blob/main/RabbitMQ/second.jpg" height="300">

4. Give `Services.msc` and make sure you check the checkbox

   <img src="https://github.com/RMohit927/Tips-Tricks/blob/main/RabbitMQ/third.jpg" height="300">

5. Select that Service from `services.msc` then you able to stop that service

   <img src="https://github.com/RMohit927/Tips-Tricks/blob/main/RabbitMQ/fourth.jpg" height="300">

6. Now download first ErLang from official site: [LINK](https://erlang.org/download/otp_win64_24.0.exe)
7. Install first ErLang Then Install RabbitMQ
8. Then download RabbitMQ From Official Site: [LINK](https://github.com/rabbitmq/rabbitmq-server/releases/download/v3.9.1/rabbitmq-server-3.9.1.exe)

Congratulation! RabbitMQ Has been Installed in your System

## Still if you not able to see `RabbitMQ Desktop` then follow below steps

1. First Open `cmd` Run As Administrator
2. goto this path `C:\Program Files\RabbitMQ Server\rabbitmq_server-3.9.1\sbin` and copy
3. open cmd and type `cd C:\Program Files\RabbitMQ Server\rabbitmq_server-3.9.1\sbin`
4. Run First `rabbitmq-plugins enable rabbitmq_management`
5. Then Run Three commands:
     1. `Rabbitmq-service stop`
     2. `Rabbitmq-service install`
     3. `Rabbitmq-service start`
     4. open browser and type `http://localhost:15672/`
     5. Congratulation! Now You are able to work with RabbitMQ Dashboard
 
Thank you!
Stay Happy, Stay Safe.
