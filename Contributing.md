# Руководство по внесению изменений

Поддерживайте ваш репозиторий обновлённым.

#### 1. Не коммитьте ничего самостоятельно в `master` вашего репозитория

Это помешает вам аккуратно обновлять ваш репозиторий, могут возникнуть конфликты.

#### 2. Прежде чем приступать к новому заданию, обновите `master`

Обновить свой репозиторий из репозитория на Гитхабе можно так:

```
# В вашей локальной копии переключитесь в ветку master
git checkout master

# Заберите изменения из репозитория на Гитхабе
git pull origin master
```

¹ В `origin` должна быть ссылка на репозиторий. Если его там нет, добавьте

```
git remote add academy <адрес репозитория на Гитхабе>
```

Когда вы обновили `master`, создайте ветку для нового задания:

```
git checkout -b module2-task1
```

`module2-task1` — это название ветки. 

--

