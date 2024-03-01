# Подсказка по GIT

### *Вносимые параметры: Имя и email*
```sh
git config --global user.name "name"
```
```sh
git config --global email.name "email"
```
*проверка текущего значения переменной*
```sh
git config user.name
```
```sh
git config email.name
```
---
---
## Вызов терминала

**Смена директории** (путь к коталогу через команду терминала)
```sh
git cd C:\folder_name
```
*Полный текущий путь*
```sh
pvd
```

## В VS Code
```sh
Open -> аналогичная папка NAME -> New fail -> Save (расширение.md)
```
---
*Отображение листинга текущей директории*

Windows
```sh
dir
```
Linux, MacOs
```sh
ls
```
---
---
# Создание репозитория
```sh
git init
```
*Сохранение изминений в VSc*
```sh
Ctrl + S
```
## Отображение статуса текущего репозитория
```sh
git status
```
## Добавление файла к отслеживанию
```sh
git add <failname.md>
```
## Фиксация изминения
```
git commit -m "comments"
```
---
---

## Все изминения (commit)
```sh
git log
```
**сжатое** отображение изминений
```sh
git log --oneline
```
## Пеерключение к определенному этапу изминений
```sh
git checkout <namecomit>
```
## Возврат на самое последние состояние
```sh
git checkout master
```
### Команда показывающая **отличия текущего измененного файла (но не зафсированного) от последнего commit** 
```sh
git diff
```
---
---
## Удаление файла с изминениями
Windows
```sh
del <failname>
```
linux, MacOs
```sh
rm <failname>
```
## Удаления изминений до commit
```sh
git restore <failname>
```

---
---
---
---
---

## Просмотр веток 
```sh
git branch
```
### Создание новой ветки
```sh
git branch <name_new_branch>
```
### Переход между ветками
```sh
git checkout <name_branch>
```
### Слияние веток 
```sh
git merge <name_branch>
```
*Находимся в головной, прописываем ту которую хотип присоеденить!*

### Удаление ветки
```sh
git branch -d <name_branch>
```
**Очистить терминал**
```sh
clear
```