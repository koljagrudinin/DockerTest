## 1. Установить Docker

## 2. 1. Запуск с помощью Docker

   cd TestDocker

   docker build -t testdocker .

   docker run -d -p 8080:80 --name myapp testdocker

## 2. 2. Запуск с помощью docker-compose

   cd TestDocker

   docker build -t testdocker .

   docker-compose up