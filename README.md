# Домашнее задание к занятию 5. "`Elasticsearch`" - `Мурчин Артем`

Dockerfile https://github.com/artmur1/14-05-hw/blob/main/Dockerfile.txt

docker-compose.yml https://github.com/artmur1/14-05-hw/blob/main/docker-compose.yml.txt

Конфиг https://github.com/artmur1/14-05-hw/blob/main/elasticsearch.yml.txt

Составил Dockerfile-манифест для Elasticsearch.

Docker-образ собрался и сам работает стабильно. Но когда запускаю через docker-compose.yml, чтобы можно было подключиться к контейнеру, секунд через 30 он останавливается.

Насройки подхватываются корректно, но скорее всего именно из-за них контейнер останавливается.

Работаю на винде10 через Virtualbox на Debian12.4. Сетевое подключение NAT, порт проброшен 2222, чтобы подключаться по SSH с винды.

Подскажите пожалуйста, почему контейнер может работать нестабильно?
