#Королев Евгений ELK
Задание 1. Elasticsearch
Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.

Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

Ответ:
![1](https://github.com/Evgenii199130/ELK/blob/main/scrin/2024-08-04%2019-52-04.png)

Задание 2. Kibana
Установите и запустите Kibana.

Приведите скриншот интерфейса Kibana на странице http://<ip вашего сервера>:5601/app/dev_tools#/console, где будет выполнен запрос GET /_cluster/health?pretty.

Ответ:

![1](https://github.com/Evgenii199130/ELK/blob/main/scrin/kibana.png)

Задание 3. Logstash
Установите и запустите Logstash и Nginx. С помощью Logstash отправьте access-лог Nginx в Elasticsearch.

Приведите скриншот интерфейса Kibana, на котором видны логи Nginx.

Ответ:

![1](https://github.com/Evgenii199130/ELK/blob/main/scrin/scrin.png)
