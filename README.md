# Лабораторная работа №5. Хранение данных. Настройки и внешние файлы
- _Выполнила:_ Кукарских Виктория
- _Язык программирования:_ Java
- _API:_ https://ntv.ifmo.ru/file/journal/идентификатор_журнала.pdf

# Что делает приложение?
Приложение состоит из 1 экрана, который позволяет:
- вводить номер нужного журнала
- скачивать этот журнал
- переходить к просмотру в подходящем приложении
- удалять файл из памяти устройства.

# Скачивание файла или действия после нажатия на кнопку "Скачать"
## 1. Проверка на получение идентификатора журнала
- если пользователь не указал ID журнала, то выведется сообщение _"Пожалуйста, введите номер журнала"_
- если пользователь указал ID журнала, то продолжится выполнение загрузки и выведется сообщение _"Файл загружается..."_

## 2. Создание папки для хранения файлов
- если Android 10+ версии, то приложению не требуется запрашивать дополнительные разрешения на доступ к хранилищу и достаточно следующего кода:

## 3. Скачивание файла
- если по указанному ID не находится журнал, то выведется сообщение _"Журнал не найден!"_
- если по указанному ID найден журнал и скачивание успешно, то все кнопки становятся активными и выводится сообщение _"Скачивание файла завершено!"_

## Просмотр загруженного файла
По нажатию на "Смотреть" откроется ботомшит с выбором подходящего приложения

## Удаление файла
По нажатию на "Удалить" файл удаляется из памяти устройства и выводится сообщение _"Файл удален"_
