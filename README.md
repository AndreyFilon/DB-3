# Домашнее задание к занятию 3 "`ELK`" - `Филон Андрей`

---

### Задание 1 Elasticsearch

Установите и запустите Elasticsearch, после чего поменяйте параметр cluster_name на случайный.  
Приведите скриншот команды 'curl -X GET 'localhost:9200/_cluster/health?pretty', сделанной на сервере с установленным Elasticsearch. Где будет виден нестандартный cluster_name.

Ответ: 

![Задание 1](https://github.com/AndreyFilon/DB-3/blob/main/elasticsearch1.jpg)  
---

### Задание 2 Memcached
   
Установите и запустите memcached.
Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.

#### Ответ:

![Задание 2](https://github.com/AndreyFilon/DB-2/blob/main/memcached.jpg)
---

### Задание 3 Удаление по TTL в Memcached

Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.
Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.

#### Ответ:

![Задание 3](https://github.com/AndreyFilon/DB-2/blob/main/key.jpg)

---

### Задание 4 Запись данных в Redis

Запишите в Redis несколько ключей с любыми именами и значениями.
Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.

#### Ответ:

![Задание4](https://github.com/AndreyFilon/DB-2/blob/main/redis.jpg)
 ---
