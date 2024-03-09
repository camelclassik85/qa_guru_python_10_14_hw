# qa_guru_python_10_14_hw

# В config.json нужно внести свои данные в поля:
"token": "Токен бота, узнается при создании"
"chat": "ID нужного чата, в котором есть бот"

# Сгенерировать репорт аалюра можно скриптом ниже после прохождения тестов:
- allure generate -c ./allure-results -o ./allure-report

# Инфа как локально/через Дженкинс запилить нотификации в мессенджеры:
https://github.com/qa-guru/allure-notifications

# Как создать бота для телеграма:
[как_создать_бота] (https://github.com/qa-guru/knowledge-base/wiki/11.-%D0%A2%D0%B5%D0%BB%D0%B5%D0%B3%D1%80%D0%B0%D0%BC-%D0%B1%D0%BE%D1%82.-%D0%9E%D1%82%D0%BF%D1%80%D0%B0%D0%B2%D0%BB%D1%8F%D0%B5%D0%BC-%D1%83%D0%B2%D0%B5%D0%B4%D0%BE%D0%BC%D0%BB%D0%B5%D0%BD%D0%B8%D1%8F-%D0%BE-%D1%80%D0%B5%D0%B7%D1%83%D0%BB%D1%8C%D1%82%D0%B0%D1%82%D0%B0%D1%85-%D0%BF%D1%80%D0%BE%D1%85%D0%BE%D0%B6%D0%B4%D0%B5%D0%BD%D0%B8%D1%8F-%D1%82%D0%B5%D1%81%D1%82%D0%BE%D0%B2)

# Для отправки нотификации нужно выполнить скрипт ниже в терминале:
java "-DconfigFile=notifications/config.json" -jar notifications/allure-notifications-4.6.1.jar
