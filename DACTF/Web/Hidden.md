# ArTiclez

## Описание

Один флаг запрятан на сайте. Если хорошенько постараться, то ты его обязательно найдешь. 

## Решение

Флаг спрятан в коде главной страницы. 

![0b2c4e9dec46beabc4c9e37b1d580fa1.png](../../_resources/0b2c4e9dec46beabc4c9e37b1d580fa1.png)

Это можно понять, если посмотреть исходный код страницы. Там будет ссылка на `about`, которого нигде нет. Также можно использовать краулер в Burp Suite и делать поиск по найденным страницам.

![08fe1003d20de87c717d41b3b839f127.png](../../_resources/08fe1003d20de87c717d41b3b839f127.png)

## Ответ

`dactf{awesome_secret_page_here}`