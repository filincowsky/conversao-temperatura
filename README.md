$ cd src/
$ docker build -t filincowsky/conversao-temperatura:aula1 .
$ docker container run -d -p 8080:8080 filincowsky/conversao-temperatura:aula1