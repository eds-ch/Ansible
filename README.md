# Ansible
Проектная работа 6

1) Для поддержки различных версий PostgreSQL необходимо добавить репозиторий.
2) Расположение базы PostgreSQL меняется в переменной в Inventory, файл hosts. Сама база в нужном месте создается вызовом команды initdb. Перед созданием идет проверка на наличие. Версия PostgreSQL меняется там же
3) Вместо CentOS 8 используется AlmaLinux.
4) Для AlmaLinux и Ubuntu используются свои репозитории Docker. Проверка OS выполняется при помощи ansible_facts. 

