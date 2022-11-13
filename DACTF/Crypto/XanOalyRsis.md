# XanOalyRsis

## Описание

Решил я как-то позаниматься криптографией. Нашёл файл и стал решать. Могу похвастаться временем прохождения ( 20 временных единиц ).

[res.txt](../../_resources/res.txt)

## Решение

Для начала скачаем инструмент CrypTool для работы с текстовым документом. Открываем текстовый документ \`res.txt\`. Заходим во вкладку \`Analysis\` -> \`Symmetric Encryption (classic)\` -> \`Ciphertext-Only\` -> \`XOR/Vemam\`.

![picture1.png](../../_resources/picture1.png)

В открывшемся окне вводим \`length = 20\` и \`hex = 20\`.

![picture2.png](../../_resources/picture2.png)

Видим hex строку.

![picture3.png](../../_resources/picture3.png)

Декодируем и получаем ответ.

![picture4.png](../../_resources/picture4.png)

## Ответ

`dactf{th3_x0r_p0w3r}`