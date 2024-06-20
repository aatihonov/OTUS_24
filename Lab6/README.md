Домашнее задание №6

VxLAN. L3VNI

Цель:
1. Настроить маршрутизацию в рамках Overlay между клиентами
2. Настроить каждого клиента в своем VNI
3. Проверить связанность между клиентами

Выполнение:

Схема сети

![image_CLOS_BGP_EVPN L3](https://github.com/aatihonov/OTUS_24/assets/169416214/f0cd32aa-53ef-4426-84db-044262f06b38)

Конфигурация оборудования

leaf1

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/84b9287e-59f4-44eb-8ae9-0f4c7917cc9a)

leaf2

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/f309c322-1efa-40b2-aa3b-bf1e39494ef6)

leaf3

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/9a9625a2-01b3-40c8-b2c6-b5d61807da79)

spine
без изменений

Проверка доступности

leaf1

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/3eaeae10-738f-4406-b6ed-588ec0a194e2)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/61bbdd76-527b-4046-b04e-c8a04ee34f45)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/2b5e1aa1-cfc2-4ee6-ab06-018875693b53)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/443fe06f-ab65-466b-8a5a-30afc150b2f3)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/729e8397-8367-40f2-ae8b-6d182585f26c)

leaf2

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/2cd309c7-1046-4f23-a460-bf06a2e029ad)

leaf3

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/68370a82-be8e-4138-b26c-bbf894acfecc)

PC

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/801cbbbd-2949-4701-9def-145101c0d11c)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/77250e38-a9ac-499e-8ea0-0a02721fa3e6)

![image](https://github.com/aatihonov/OTUS_24/assets/169416214/b1124bb6-62d1-4214-950f-b53e32c266bf)










