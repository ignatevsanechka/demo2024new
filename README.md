# demo2024new
# Таблица адресации
| Имя устройства | Итерфейс |  IPv4/IPv6   | Маска/Префикс |       Шлюз       |
| -------------- | -------- | ------------ | ------------- |    ----------    |
|                | ens 192  | 10.12.17.5  | /24           | 10.12.25.254     |
| ISP            | ens 224  | 192.168.0.162| /30           |                  |
|                | ens 256  | 192.168.0.166| /30           |                  |
| HQ-R           | ens 192  | 192.168.0.1  | /25           |                  |
|                | ens 224  | 192.168.0.161| /30           | 192.168.0.162    |
| BR-R           | ens 192  | 192.168.0.129| /27           |                  |
|                | ens 224  | 192.168.0.165| /30           | 192.168.0.166    |
| HQ-SRV         | ens 192  | 192.168.0.126  | /25           | 192.168.0.1      |
| BR-SRV         | ens 192  | 192.168.0.130| /27           | 192.168.0.129    |
## Установка Docker
