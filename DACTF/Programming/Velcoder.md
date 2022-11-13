# Velcoder

## Описание

Держи файл, дальше сам...


[stangesh1t.txt](../../_resources/stangesh1t.txt)


## Решение

Если открыть файл, то увидим перед собой base64 код, который мы не сможем декодировать онлайн, так как он слишком большой.

Окей, тогда напишем автоматизацию

```python
import base64

buf = ''

with open("stangesh1t.txt", 'r+', encoding='utf8') as f:
    buf = f.read().encode()
   
while True:
    try:    
        buf = base64.b64decode(buf)
        #print(buf)
    except Exception:
        print("flag: ", buf.decode())
        exit()
```

## Ответ

`narfuctf{omg_50/base64_r333aly?}`