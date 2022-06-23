# CodeIgniter4-Docker-Apache-PHP-MySQL

**1**. Установка в текущую папку с очисткой git папок 
```
git clone https://github.com/wpdew-com/docker_for_codeigniter .; rd .gitignore; rd readme.md; rm -r -fo .git
```

**2**. Создайте контейнеры и запустите их.

* Выполните команду для старта проэкта:

```shell script
docker-compose build
```

Создание контейнеров займёт некоторое время. Дождитесь окончания процесса. Ваш компьютер не должен во время данного процесса потерять доступ в интернет.  
<hr/>

* Запуск контейнера для работы
```shell script
docker-compose up -d
```
* Остановка контейнера
```shell script
docker-compose down
```
* Доступ к сайту по адресу [http://localhost/](http://localhost/)
