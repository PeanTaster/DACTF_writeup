# Such a lot Types of contents

## Описание

Я бы сказал, что хэш роляет, но на самом деле нет. 

Верху бред, не обращай внимания. Это самая обычная стега.


[Rolling hash.docx](https://github.com/PeanTaster/DACTF_writeup/blob/main/_resources/Rolling%20hash.docx?raw=true)


## Решение

Если знать структуру документа docx или хотя бы то, что он является zip архивом, то это задание окажется не таким уж и сложным. Для того, чтобы его решить требутся открыть документ любым архиватором и посмотреть содержимое. 

Название задания намекает на файл, куда нужно смотреть.

Заходим в файл `[Content_Types].xml` и видим сообщение: 

```
<!--
      Hello,
         I am a multi-line XML comment
			your flag is narfuctf{omg_1s_all_wolrd_an_archive?}
-->
```

## Ответ

`narfuctf{omg_1s_all_wolrd_an_archive?}`
