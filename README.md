# Домашнее задание к занятию "Memcached & Redis homework - Гурылев А.В."

Задание 1. Кеширование
Приведите примеры проблем, которые может решить кеширование.

Повышение производительности достигается за счет
складывания в кэш данных, к которым чаще всего происходит
обращение;
● Увеличение скорости ответа;
● Экономия ресурсов базы данных, например, применяя
кэширование тяжелых запросов;
● Сглаживание бустов трафика. Например, во время черной
пятницы онлайн-магазины используют кэш, чтобы переживать
резкое увеличение трафика. 

Задание 2. Memcached
Установите и запустите memcached.

![alt text](https://github.com/A1ex93/memcached_radis_homework/blob/main/image/1.png)

Приведите скриншот systemctl status memcached, где будет видно, что memcached запущен.

Задание 3. Удаление по TTL в Memcached
Запишите в memcached несколько ключей с любыми именами и значениями, для которых выставлен TTL 5.

![alt text](https://github.com/A1ex93/memcached_radis_homework/blob/main/image/2.png)

Приведите скриншот, на котором видно, что спустя 5 секунд ключи удалились из базы.

Задание 4. Запись данных в Redis
Запишите в Redis несколько ключей с любыми именами и значениями.

![alt text](https://github.com/A1ex93/memcached_radis_homework/blob/main/image/3.png)

Через redis-cli достаньте все записанные ключи и значения из базы, приведите скриншот этой операции.
![alt text](https://github.com/A1ex93/memcached_radis_homework/blob/main/image/4.png)
