﻿Sinrel Launcher Engine
======================

SLE ( Sinrel Launcher Engine ) — это движок позволяющий создавать Minecraft-лаунчеры практически любой сложности.

Версия
======

Текущая версия
--------------
0.3.2.7

Модель версии
----------------

x1.x2.x3.x4

* 1) Поколение 
* 2) Версия движка (Java часть)
* 3) Версия серверной части (PHP часть)
* 4) Исправление

Примечание
----------

SLE в данный момент находится в стадии разработки. Создание каких-либо коммерческих продуктов на нём не предпочтительно в связи с его незавершенностью.

Процесс разработки
------------------

При разработке на движке SLE разработчику фактически остаётся писать только графический интерфейс (GUI), что весьма значительно сокращает сроки разработки лаунчера.

Лаунчер состоит из двух элементов:
* 1. Главного класса

	Главный класс должен наследоваться от класса JavaLauncher, который содержит необходимые служебные методы.

* 2. Описывающего файла ( launcher.properties ) который должен находится в корне проекта, а позже в корне jar-файла

Лицензия
--------
Только ознакомление (будет изменено после релиза)

