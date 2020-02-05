# Система сборки: build, test and deploy
https://github.com/ + https://travis-ci.org/ + https://bintray.com/

## Проверка
Задание считается выполнено успешно, если после подключения репозитория
```
$ echo "deb http://dl.bintray.com/login/otus-cpp xenial main" \
| tee -a /etc/apt/sources.list.d/otus.list
```
установки пакета
```
$ apt update && apt install -y helloworld
```
запуска бинарного файла
```
$ helloworld
```
появилось сообщение
```
build N
Hello, World!
```
