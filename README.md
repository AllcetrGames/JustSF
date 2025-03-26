# GitFS #1.0
Репозиторий для модуля GitFS (GitFileSharing)

# СОЗДАНИЕ ФАЙЛА

Сначала создайте репозиторий с любым названием. В нем созздайте текстовый файл c любым именнем. Далее выберите тип файла: **Текст (text)** и напишите в текстовый файл
```type=text```
Потом напишите само содержимое запроса. 
# ЕСЛИ СОДЕРЖИМОЕ: ТЕКСТ

Напишите **content=** и сам текст.
```content=Текст```

Тестовый файл с **типом текст** с текстом **Hello world**:

``` shell
content=Hello world
type=text
```
# ПЕРЕНОС НА JUSTMC

Сначала загрузите модуль JustFS.
```/module load AllcetrGD/gitfs```
Затем перейдите в репозиторий и откройте свой файл. Потом нажмите **Raw** и скопируйте ссылку нового окна.

![2025-03-25_22-56-56](https://github.com/user-attachments/assets/63d45995-038c-4969-9805-0fad1318e47e)

После перейдите в **/play** и пропишите:
``` shell
#get Ссылка
```
Если всё будет хорошо то вам либо выдаст текст в чат либо карту с вашей картинкой.
