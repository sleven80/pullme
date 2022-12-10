# Шпаргалка по GIT

**Cистема контроля версий (VCS)** — программное обеспечение для облегчения работы с изменяющейся информацией.

* **Полная история изменений каждого файла за длительный период**. Это касается всех изменений, внесесннных огромным количеством людей за долгие годы. Изменением считается создание и удаление файлов, а также редактирование их содержимого. Различные инструменты VCS тем насколько хорошо они обрабатывают операции переименования и перемещения файлов. в историю также должны входить сведения об авторе, дата и комментарий с описанием цели каждого изменения. Наличие полной истории позволяет возвращаться к предыдущим версиям, чтобы проводить анализ основных причин возникновения ошибок и устранять проблемы. Наличие полной истории позволяет возвращаться к предыдущим версиям, чтобы проводить анализ основных причин возникновения ошибок и устранять проблемыы в старых версиях программного обеспечения.

* **Ветвление и слияние**. Создание веток позволяет иметь несколько независимых друг от друга направленийи разработки, а также выполнять их слияние, чтобы разработчики могли проверить, что изменения, внесенные в каждую из веток, не конфликтуют друг с другом. Многие команды разработчиков программного обеспечения создают отдельноые ветки для каждого функциональной возможности, для каждого релиза либо и для того, и для другого.

* **Отслеживаемость.** Возможность отслеживать каждое изменение, внесенное в программное обеспечение, и связывать его с ПО для управления проектами и отслеживания ошибок. История с комментариями во время чтения кода помогает понять, что этот код делает и почему действие реализовано именно таким образом. Благодаря этому разработчики могутт вносить корректные и совместимые изменения в соответствии с долгосрочным планом разработки системы.

### Подготовка к работе
1. Скачать и установить VS Code https://code.visualstudio.com/docs/?dv=win
2. Скачать и установить Git https://git-scm.com/download/win
3. Проверить, работает ли git  с помощью команды 
git --version
4. Добавить имя и email пользователя с помощью команд

    'git config --global user.email "email@mail.com"'

    'git config --global user.name "User Name"'