cd TestDocker
docker build -t testdocker .
docker run -d -p 8080:80 --name myapp testdocker

Либо

cd TestDocker
docker build -t testdocker .
docker-compose up