# Подсказка по GIT

### *Вносимые параметры: Имя и email*
```sh
config --global user.name "name"
```
```sh
config --global email.name "email"
```
*проверка текущего значения переменной*
```sh
config user.name
```
```sh
config email.name
```
**Вызов терминала**

**Смена директории** (путь к коталогу через команду терминала)
```sh
cd C:\folder_name
```
состояние текущей папки изменено

**Полный текущий путь**
```sh
pvd
```

В VS Code 
```sh
Open -> аналогичная папка NAME -> New fail -> Save (расширение.md)
```
Отображение листинга текущей директории

Windows
```sh
dir
```
Linux, MacOs
```sh
ls
```

```sh
init
```
Сохранение изминений в VSc
```sh
Ctrl + C
```
Отображение статуса текущего репозитория
```sh
status
```
Добавление файла к отслеживанию
```sh
add <failname>
```

Фиксация изминения
```
commit -m "comments"
```
Удаление файла с изминениями

Windows
```sh
del <failname>
```
linux, MacOs
```sh
rm <failname>
```

Все изминения (commit)
```sh
log
```
сжатое отображение изминений
```sh
log --oneline
```
Пеерключение к определенному этапу изминений
```sh
checkout <34a8159>
```
Возврат на самое последние состояние
```sh
checkout master
```
Команда показываюшая отличия текущего измененного файла (но не зафсированного)от последнего commit 
```sh
diff
```