|[< На главную](readme.md)|
|-|

## git commit

Команда сохраняет слепок проиндексированных файлов с текущими изменениями во внутренней базе данных:

```
git commit
```
Команда откроет текстовый редактор в терминале, где можно добавить комментарии, описать изменения.

Если в вызове текстового редактора нет необходимости, команду можно вызвать с флагом **-m** и вписать однострочный комментарий:

```
git commit -m "message"
```

Если после коммита была обнаружена ошибка в комментарии, исправить его поможет флаг **--amend** перед **-m** с правильным описанием изменений:

```
git commit --amend -m "New message"
```
Если во время коммита не былизафиксированы некоторые файлы или папки, их можно подготовить к фиксации и воспользоваться флагами **--amend** и **--no-edit** (последний позволяет зафиксировать изменения без редактирования комментария):

```
git commit --amend --no-edit
```

Команда **git log** позволяет просмотреть историю изменений

| Далее: [git log](gitlog.md) |  
|-|  