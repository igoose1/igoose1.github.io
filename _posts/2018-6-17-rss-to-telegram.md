---
layout: post
title: Публикации в telegram
---

У блога есть [канал в telegram](https://t.me/igoose_me).
Туда попадают новости, ради которых не хотелось бы писать целый пост.

Например:

<script async src="https://telegram.org/js/telegram-widget.js?4" data-telegram-post="igoose_me/7" data-width="100%"></script>


Я только что прикрепил туда публикацию новых постов с блога.

Сделал с помощью [IFTTT](https://ifttt.com).
Их сервис просто монитор [RSS ленту блога](https://igoose.me/feed.xml) (а она есть), а затем выкладывает новое сообщение в канале.

На самом деле я еще не тестировал эту функцию, поэтому решил написать этот пост.
Сейчас посмотрим.

UPD:

Мда, это не то, что я ожидал.

![Сообщение в канале от IFTTT][ifttt-message]

UPD:

Ее, это оно.
Только мне пришлось свой applet создавать.

![Сообщение в канале от IFTTT][ifttt-message]


[post-example-image]: {{ "/images/Hello-World/example.jpg" | absolute_url }}
[ifttt-message]: {{ "/images/rss-to-telegram/ifttt-message.png" | absolute_url }}
