# Zabbix-Keenetik-4G
Zabbix template for Keenetik/Netcraze router measure LTE network parameters by supported internal/external 4G modem

Шаблон для Zabbix для роутеров Keenetik/Netcraze для измерения параметров мобильной сети LTE встроенными или внешними модемами 4G.

Основные OID  имена параметров импортированы из  CISCO-WAN-3G-MIB и CISCO-WAN-CELL-EXT-MIB.

Всего используется/реализовано 2 дерева OID:

.1.3.6.1.4.1.9.9.661.1.3.4.1.1.1 (CISCO-WAN-3G-MIB)

.1.3.6.1.4.1.9.9.817.1.1.1.1.1 (CISCO-WAN-CELL-EXT-MIB)

Макросы LLD шаблона обнаруживают все имеющиеся на роутере модемы 4G, индекс устройства содержится  в значении параметра - например, RSSI[29].

