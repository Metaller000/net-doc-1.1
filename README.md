# Отчет по sk

## Задание 1. Образы и контейнеры Docker
### скриншот вывода результатов команды ifconfig (на Kali Linux) или ip a (на Ubuntu);
![Image alt](assets/1.1.png "")

### скриншот вывода результатов команды sudo docker pull bash;
![Image alt](assets/1.2.png "")

### скриншот вывода результатов команды sudo docker run -it bash;
![Image alt](assets/1.3.png "")

### скриншот вывода результатов команды sudo docker stop names;
![Image alt](assets/1.4.png "")

### скриншот вывода результатов команды sudo docker rm names;
![Image alt](assets/1.5.png "") 
 
### скриншот вывода результатов команды sudo docker rmi repository;
![Image alt](assets/1.6.png "")

### скриншот вывода результатов команды sudo docker ps -a;
![Image alt](assets/1.7.png "")

### скриншот вывода результатов команды sudo docker image ls.
![Image alt](assets/1.8.png "")

## Задание 2. Bash в Docker
### скриншот вывода результатов команды sudo docker run –rm -it bash;
![Image alt](assets/2.1.png "")

### скриншот вывода результатов команды whoami и cat /etc/*release* (в контейнере);
![Image alt](assets/2.2.png "")

### скриншот вывода результатов команды ls -la / (в контейнере);
![Image alt](assets/2.3.png "")

### скриншот вывода результатов команды whoami и cat /etc/*release* (в основной системе);
![Image alt](assets/2.4.png "")

### скриншот вывода результатов команды ls -la / (в основной системе).
![Image alt](assets/2.5.png "")

## Задание 3. Dockerfile
### скриншот вывода содержимого файла скрипта cat my_bash_1.sh (необходимо указывать назначенное вами имя скрипта);
![Image alt](assets/3.1.png "")

### скриншот вывода содержимого файла Dockerfile cat Dockerfile;
![Image alt](assets/3.2.png "")

### скриншот результатов сборки образа sudo docker build -t image_bash_1 . (необходимо указывать назначенное вами имя 
![Image alt](assets/3.3.png "")
образа);

### скриншот результатов запуска контейнера sudo docker run –rm image_bash_1 (необходимо указывать назначенное вами имя образа);
![Image alt](assets/3.4.png "") 


### скриншот результатов запуска скрипта в основной системе ./my_bash_1.sh (необходимо указывать назначенное вами имя скрипта).
![Image alt](assets/3.5.png "")

## Задание 4. Docker-compose
### скриншот вывода содержимого подготовленного вами файла index.html, содержащий ваше Ф.И.О.;
![Image alt](assets/4.1.png "")

### скриншот вывода содержимого подготовленного вами файла docker-compose.yml;
![Image alt](assets/4.2.png "")

### скриншот результатов запуска подготовленной вами связки контейнеров;
![Image alt](assets/4.3.png "")

### скриншот первоначальной титульной страницы Nginx при подключении браузером к контейнеру;
![Image alt](assets/4.4.png "")

### скриншот запуска связки контейнеров после замены файла index.html в контейнере, содержащий ваше Ф.И.О.;
![Image alt](assets/4.5.png "")

### скриншот вашего варианта титульной страницы Nginx при подключении браузером к контейнеру, содержащий ваше Ф.И.О.;
![Image alt](assets/4.6.png "")

### скриншот вывода результатов команды остановки связки контейнеров.
![Image alt](assets/4.7.png "")

