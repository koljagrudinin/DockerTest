#. Установить Docker

##. Запуск с помощью Docker

   cd TestDocker

   docker build -t testdocker .

   docker run -d -p 8080:80 --name myapp testdocker

##. Запуск с помощью docker-compose

   cd TestDocker

   docker build -t testdocker .

   docker-compose up