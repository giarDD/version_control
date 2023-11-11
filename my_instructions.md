## GOOD DAY 

# Заголовки

Чтобы сделать заголовок нужно ввести хэштег и писать дальше

Пример: # Вот так

Чтобы сделать заголовок меньше нужно ввести 2 хэштега

Пример: ## Вот так


# Оформление текста

Чтобы писать курсивом выделяй текст звездочкой

Пример: *Текст*

Чтобы писать жирно выделяй двумя 

Пример: **Текст**

# Списки

Чтобы сделать нумерованный список просто пиши цифру точку и текст

Пример:

1. Первое
2. Второе
3. Третье

Чтобы сделать ненумерованный список просто пиши * и текст

Пример:

* первое
* второе
* третье


# Ссылки

Чтобы сделать ссылки пиши вот так

[hello world](hello.world/ "привет мир")


# Работа с удалёнными репозиториями

Добавить удалённый репозиторий можно параметром remote add, указав shortname и url требуемого репозитория.

```sh
git remote add awesomeapp https://github.com/someurl..
```

Просматривать удалённые URL-адреса можно параметром remote с флагом -v. Этот параметр отображает удалённые подключения к другим репозиториям.

```sh
git remote -v
```

Получить подробные сведения об удалённом репозитории можно с помощью параметра remote show с указанием имени репозитория — например, origin


```sh
git remote show origin
```

Отправлять изменения в удалённый репозиторий можно параметром push с указанием имени репозитория и ветки.

```sh
git push origin main
```

Для загрузки изменений из удалённого репозитория используется параметр pull. Он скачивает копию текущей ветки с указанного удалённого репозитория и объединяет её с локальной копией.

```sh
git pull
```
