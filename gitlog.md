|[< На главную](readme.md)|
|-|

## git log
Выводит список коммитов

```
git log
```

Данная команда выводит список коммитов с именем автора, датой и комментариями к коммитам. Однако выводить историю можно в каком угодно формате. 

Однострочный:

```
git log --pretty=oneline
```

В формате *хэш - автор, дата : комментарий*:

```
git log --pretty=format:"%h - %an, %ad : %s"
```

| Далее: [git show](gitshow.md) |
|-|