# Загрузка отчета о платном хранении на складе Wildberries через API сервиса.

## Задача
Необходимо создать программу (скрипт), выгружающую отчет о платном хранении товаров на складе Wildberries через API сервиса.
## Техническое задание
1. Выгружать все данные по данному отчету;
2. Возможность установки периода выгрузки, с учетом того что выгрузка будет производиться раз в неделю;
3. Программа, по возможности, не должна требовать установки и настройки дополнительного ПО. Штатно используется MS Excel;
4. Должна быть возможность сохранения конечного результата (таблицы) в файл формата csv или xlsx;
5. Программа должна требовать минимального обслуживания (доработок) при возможных изменениях на стороне Wildberries.
## Исполнение
Для реализации задачи выбрано ПО MS Excel и его компоненты. Реализована следующая логика работы.
Пользователю необходимо вставить API-ключ в соответствующее поле, далее установить требуемый интервал отчета.
Далее отправить запрос на формирование отчета и затем отправить запрос на получение отчета.
Для этого использовать соответсвующие кнопки на панели интерфейса.
Результат в виде отчета сохранить в файл в удобном формате.
## Инструменты
Excel, Power Query, VBA
## Решение
[Загрузить (xlsm)](https://disk.yandex.ru/d/-6r-YBZDsPbRXw)
