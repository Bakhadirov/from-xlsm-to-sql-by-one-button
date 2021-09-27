# from-xlsm-to-sql-by-one-button
Script from xlsm to sql by one button
Задача:
Создать скрипт upload.py и из него исполняемый файл upload.exe, запускаемый по кнопке "Загрузить"* в файле "названия точек.xlsm",
для загрузки/обновления данных из файла в таблицу в БД Postgres. 
*При нажатии кнопки, VBA макрос(уже есть в файле "названия точек.xlsm") запускает upload.exe с аргументом (путь до файла "названия точек.xlsm")

Скрипт создан, работоспособен.
Необходимо установить следующие библиотеки: pandas, sqlalchemy
В файле configure.ini для подключения к необходимой базе данных необходимо в "name" прописать необходимые данные (логин, пароль)

To download:
https://github.com/Bakhadirov/from-xlsm-to-sql-by-one-button/releases/tag/alpha 

