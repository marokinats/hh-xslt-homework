# hh-scool-xsml


## XML

Жду от вас вдумчивой разметки данных

Элементы и атрибуты в camalCase


## XLS

За шаблоны без mode буду снимать баллы

Имена шаблонов в kebab-case

Структуру шаблонов разработайте исходя из здравого смысла

В xml нужно разметить коллекцию данных общих для всего документа, например: валюту, и использовать данные из этой коллекции с помощью [ключей](https://xsltdev.ru/xslt/xsl-key/)


Во время работы делайте коммиты с логически законченными кусками кода: описали меню в xml, добавили для меню шаблоны - закоммители. Коммиты описывайте, пожалуйста, так чтобы из них был понятен смысл происходящего в добавленном коде.


Удачи. Я в вас верю! ;)

P.S. Крайний срок близко - 23.12.2019

## Запуск на windows:
----преобразование
    msxsl doc.xml index.xsl -o index.html
----преобразование и поднятие localhost
    yarn proc-dev