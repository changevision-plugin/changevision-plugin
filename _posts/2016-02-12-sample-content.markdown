---
layout: default
title:  "Установка и настройка плагина для DataLife Engine"
date:   2016-02-12 17:50:00
categories: main
---

Установка для DLE осуществляется следующим образом.<br>
1.	Загруженную папку с GitHub поместить в папку modules по пути \engine\modules.<br>
2.	Открыть файл main.tpl по пути \templates\{Название вашего шаблона}.<br>
3.	Вставить строку.
{include file="engine/modules/changevision/changevision.php"}.
 в main.tpl после тега <body>.<br>
4.	Готово!<br>
