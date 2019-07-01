# Statistics Ads

A simple accounting system for users of various Internet resources on which an ad unit is installed, and according to which users made clicks.

## Live preview
You can see a live demo of the template:

* [Preview](http://statistics.ang.center)

#TECH
- Apache 2
- PHP 5.6+
- MySQL
- BootStrap
- JS no JQUERY

1. Выделенный сервер Linux.
2. Выполняется на PHP5.6 без использования фреймворков и сторонних библиотек.
3. Задание выполняется с использованием javascript без jquery или любых других библиотек.
4. База данных: MySQL.



## Простая система учета пользователей различных интернет-ресурсов, на
которых установлен рекламный блок, и по которому пользователи сделали клики.
1. Интернет-ресурсы.
Возможность добавлять, редактировать, удалять любой интернет-ресурс, а также видеть список его
рекламных блоков.
Основные свойства интернет-ресурса: url, тематика (список тематик должен храниться в отдельной
таблице), контакт для связи.
Просмотр списка интернет ресурсов по умолчанию 15 на страницу, сортировка по id по убыванию.
2.Рекламный блок.
Возможность добавлять, редактировать, удалять любой рекламный блок.
Основные свойства рекламного блока: название, ID интернет-ресурса, описание.
Возможность взятия JS-кода рекламного блока для размещения в html-коде интернет-ресурса
(подразумевается, что на странице списка рекламных блоков для каждого будет своя кнопка, при
клике на которую будет показана область, с которой можно скопировать сгенерированный системой
JS-код для размещения на html-странице сайта).
3.Статистика показов.
Основные свойства статистики: ID интернет-ресурса, ID рекламного блока, дата показа рекламного
блока, количество показов рекламного блока, IP адрес пользователя, ISO код страны пользователя
4.Статистика кликов.
Основные свойства статистики: ID интернет-ресурса, ID рекламного блока, дата и время клика по
рекламному блоку, IP адрес пользователя, ISO код страны пользователя.
5.Общая статистика.
На странице общей статистики нужно вывести список записей объединенных таблиц статистики
показов и кликов, по умолчанию сгруппированных по дате. Также должна быть возможность
сгруппировать по ID рекламного блока, ID интернет-ресурса, и ISO коду страны.
Поля для отображения: поле группировки (дата показа, ID рекламного блока, ID интернет-ресурса,
ISO коду страны), количество показов, количество кликов.
На странице общей статистики должны быть 2 фильтра:
- для выбора дат начала и конца периода выборки результатов из таблиц статистики
- для поля группировки, реализованный на javascript, работающий в момент ввода данных (без
перезагрузки страницы и без использования технологии ajax, т.е. нужно выполнять фильтрацию по
уже загруженным данным на странице).
*Учестены все возможные ситуации при удалении одного из параметров в системе и
влияние на дальнейшую работу в целом.
