# Zabbix шаблон для системы видеонаблюдения Линия (Devline)
Взял у https://github.com/dobriydenis/zabbix-devline , поправил версию питона, допишу(сал) комментарий по установке (наверное для себя, чтобы не забыть)

 1.  ```apt install python3 python3-pip && pip install xmltodict```

2) Ставим скрипты в папку указанную как размещение внешних скриптов (параметр 'ExternalScripts' в файле конфигурации Zabbix сервера), меняем хозяина файлов на zabbix:zabbix, даём права на исполнение файла +x

4) Импортируем шаблон
5) Заполняем макросы: ```{$USER_LINE} - имя пользователя в DevLine 
                         {$PASSWORD_LINE} - пароль пользователя```
6. Наслаждаемся тем, что всё не работает :)
