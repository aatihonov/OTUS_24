Домашнее задание №7

VXLAN. Multihoming.

Цель:
1. Настроить отказоустойчивое подключение клиентов с использованием EVPN Multihoming.
2. Подключить клиентов 2-я линками к различным Leaf.
3. Настроить агрегированный канал со стороны клиента.
4. Настроить multihoming для работы в Overlay сети.
5. Убедиться, что связность не теряется при отключении одного из линков.

Выполнение:
Схема сети

![image_CLOS_BGP_EVPN L3_MH](https://github.com/aatihonov/OTUS_24/assets/169416214/5aff28ca-11f1-4f05-ac80-87ee7524004f)

Конфигурация оборудования

во вложенных файлах (конфиг уже большой, 1-й картинкой не вставить).

Проверка доступности

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/e0905005-83a4-4642-bdc4-2a5a806df9c8)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/10d728bf-10d4-4c0f-833f-84e527258923)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/e0eb5a87-984b-4d9f-b6c7-bfe0377e862e)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/12c27bdc-15d1-4b8a-8b7b-07d36bdce342)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/d6ed4f0e-6ca6-4588-a817-5630a42749f6)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/802ad264-1177-48cd-b0b4-3dc9ab7f258f)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/f800b1ae-de7c-4816-8d5a-39ffb35119f8)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/92dcbdbb-aab1-4ea0-89c9-4be0b7c32ac2)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/337e14f7-fa3b-4c74-8f09-ee80d8069f98)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/bf297f62-607f-4572-89bd-55f531d6d2ef)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/5ab430ce-70da-4584-b1ff-6b2577c079a5)

Убедиться, что связность не теряется при отключении одного из линков.

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/e229b18d-b47f-492c-bf7d-113eb229e68b)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/dcdba977-366b-4e31-bbb2-a075218a2198)












