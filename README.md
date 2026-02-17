# free-games

## Как забрать у меня «новый код» (для новичка)

Весь проект находится в одном файле: **`index.html`**.

### 1) Показать путь к файлу
```bash
pwd
```
Откроется папка проекта. В ней и лежит `index.html`.

### 2) Сделать копию с новым кодом
```bash
cp index.html updated-index.html
```
Теперь файл `updated-index.html` — это тот самый обновлённый код целиком.

### 3) Открыть и скопировать полностью
- Открой `updated-index.html` в редакторе.
- Нажми `Ctrl + A` → `Ctrl + C`.
- Вставь куда нужно `Ctrl + V`.

### 4) Если нужно отправить на GitHub
```bash
git add index.html
git commit -m "Update index.html"
git push origin work
```
Потом на GitHub:
1. Открой Pull Request `work -> main`.
2. Нажми `Merge pull request`.

---

Если нужно, можно просто выполнить:
```bash
cat index.html
```
Это выведет **весь** обновлённый код в терминал.
