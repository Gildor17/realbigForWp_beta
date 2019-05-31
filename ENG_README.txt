=== Realbig For WordPress ===
Contributors: 101
Tags: AD, content filling
Requires at least: 4.0
Tested up to: 4.9.6
Stable tag: 0.1.4a
Requires PHP: 5.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Realbig plugin for wordpress

== Description ==
--
AD blocks Positioning within content

== Installation ==
+-
still not on English

Plugin installation and configuration:
Realbig side:

- Sign up your site on realbig;
- Create and configurate at least 1 block for this site;
- Proceed to the positions configuration page using "ВП плагин" tab or "WP" button in your choosed site line;
- Choose the site (if you proceed on this page by using "ВП плагин" tab);
- You will see your token for chosen site below it;
- Configurate blocks positions for showing them on the pages of the site you have chosen and save it;

From the side of your  wordpress's site:

- Download plugin;
- Activate plugin on your site;
- After activation, proceed to "realbig" tab, where input token in "Токен" field, which is taken from Realbig, and synchronise.

Tips:

block settings definition:
1) "блок" - block's name, configured for site in "сайты" tab;
2) "тип отображения" - choose placing type of blocks:
2.1) "одиночный блок" - blocks is placed via using HTML-tags;
2.2) "конкретный элемент" - blocks is placed via using ids/classes;
2.3) "в конце контента" - block is placed in the end of content (usually, before comments);
3) "тег" - HTML-tag, near whick AD is placed;
4) "позиция тега" - before/after tag position;
5) "место тега" - выбор номера тега по счету, относительно которого будет вставлятся блок, при положительном значении считает теги с начала контента до конца, а при отрицательном значении считает блоки с конца контента;
6) "конкретный элемент" - название ид/класса элемента (писать в форматах "#название_ид/.название_класса"), возле которого ставится блок;
7) "минимум символов" - минимальное количество символов в контенте, которое нужно, что бы блок отображался (0 или пусто - без ограничений);
8) "минимум заголовков" - минимальное количество заголовков (h1-h6) в контенте, которое нужно, что бы блок отображался (0 или пусто - без ограничений), основной заголовок тоже учитывается;
9) "активный" (checkbox) - активация или деактивация блока. Неактивные блоки не учитываются при синхронизации;
10) "удалить" - удаление настроек для блока;

- "Добавить скрипт для PUSH в head сайта" (checkbox) - при включении, после сохранения и синхронизации, плагин будет вставлять в Head сайта код, который нужен для работи PUSH;

- На RealBig, на странице "ВП плагин", ваш блок должен быть отмечен, как "активный", что бы при синхронизации настройки для этого блока учитывались.

по статусам:

success - успех, все исполнено удачно;
no changes from last sync - срабатывает только при автосинхронизации, значит, что с момента последней синхронизации не изменялись настройки для плагина;
no token - отправлен (получен) пустой токен;
wrong token - неверный токен;
You have no configured blocks for this site - нету ни одной настройки для плагина по этому токену;
ошибка запроса на сервер - получен не "POST" запрос;
ошибка соединения - нету ответа от Реалбиг;
unexpected error - любаю другая ошибка;
			
== Changelog ==

= 0.1 =

Первая стабильная версия.

== Upgrade Notice ==
