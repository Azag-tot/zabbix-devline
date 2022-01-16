# Zabbix шаблон для системы видеонаблюдения Линия (Devline)
Взял у https://github.com/dobriydenis/zabbix-devline , поправил версию питона, допишу(сал) комментарий по установке
1) apt install python3 python3-pip && pip install xmltodict
2) Ставим скрипты в папку указанную как размещение внешних скриптов (параметр 'ExternalScripts' в файле конфигурации Zabbix сервера), меняем хозяина файлов на zabbix, даём права на исполнение файла +x
3) Импортируем шаблон
