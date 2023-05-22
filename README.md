# net1
1.Шаг 1. Работа c HTTP через telnet.
    Подключитесь утилитой telnet к сайту stackoverflow.com:
telnet stackoverflow.com 80
    Отправьте HTTP-запрос:
GET /questions HTTP/1.0
HOST: stackoverflow.com
[press enter]
[press enter]
В ответе укажите полученный HTTP-код и поясните, что он означает.
![изображение](https://github.com/Razbor/net1/assets/19568831/5717863e-7dc8-480a-8584-f34b5ef568e2)
HTTP 403 Forbidden — стандартный код ответа HTTP, означающий, что доступ к запрошенному ресурсу запрещен

2.Повторите задание 1 в браузере, используя консоль разработчика F12
![изображение](https://github.com/Razbor/net1/assets/19568831/8a7793d8-548a-44c7-b9b1-6bb851070f39)
![изображение](https://github.com/Razbor/net1/assets/19568831/c684bf50-25b6-4efe-8adb-aefb0025d451)

3.Какой IP-адрес у вас в интернете?
![изображение](https://github.com/Razbor/net1/assets/19568831/a31fcd4f-1042-4ecc-b7a3-10cde3d17840)

4.Какому провайдеру принадлежит ваш IP-адрес? Какой автономной системе AS? Воспользуйтесь утилитой whois.
Принадлежит провайдеру Интерсвязь
![изображение](https://github.com/Razbor/net1/assets/19568831/5548e954-c529-4b88-9532-621e5b1244df)
Автономная система  AS8369
![изображение](https://github.com/Razbor/net1/assets/19568831/2599d91a-9d05-4a28-ab25-8ffba297165f)

5. Через какие сети проходит пакет, отправленный с вашего компьютера на адрес 8.8.8.8? Через какие AS? Воспользуйтесь утилитой traceroute
![изображение](https://github.com/Razbor/net1/assets/19568831/e984d8e1-7e72-4005-be95-61be8f53c70f)

6. Повторите задание 5 в утилите mtr. На каком участке наибольшая задержка — delay?
![изображение](https://github.com/Razbor/net1/assets/19568831/de47e869-436f-41f6-8fe5-253e3e0c4aa7)
Наибольшая задержка на узле 216.239.47.201
7.Какие DNS-сервера отвечают за доменное имя dns.google? Какие A-записи? Воспользуйтесь утилитой dig
![изображение](https://github.com/Razbor/net1/assets/19568831/1c6303c1-5738-4e35-bde2-fe459ce17557)


