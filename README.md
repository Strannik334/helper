#команды консоли
1. pwd - показывает путь к тому, где ты сейчас находишься.
2. cd - перемещает тебя вперёд по файлам и папкам.
3. .. - перпемещает назад по файлам и папкам.
4. touch - создаё файл.
5. mkdir - создаёт директорию. 
6. cp - копирует файл.
7. mv - перемещает файл.
8. cat - выводит на экран содержимое файла.
9. rm, rmdir - удаляют файл/директорию.
10. && - позволяет использовать несколько команд в одной строке.
11. ls - показывает список файлов и папок в теккущей папке.
12. git init - делает папку  Git-репозиторием.
13. rm -rf .git - разгичивает папку.
14. git status - показывает состояние репозитория.
15. git add - подготовка файла к сохранению.
16. git commit - делаем коммит.
17. git log - позволяет просмотреть историю коммитов.
18. ssh-keygen - создаёт ключ.
19. clip - копирует в буфер обмена информацию из файла.
20. git remote add - соединяет удалённыый репозиторий и локальный.
21. git remote -v - позволяет убедиться в связи репозиториев.
22. git push - отправляет изменения на удалённый репозиторий.
# Работа с Markdown
заголовки:

# hi
## git 
### and
#### world

текст над чертой

---

текст под чертой

разрыв строки с помощью пробелов (2 пробела)

_курсив_ - *курсив* (по одной звёздоче по краям или нижним подчёркиваем)
**полужирный** (по две звёздочки по краям)
~~зачёркнутый текст~~ (по две тильды по краям)

нумерованный список был выше
код с помощью трёх грависов вначале и в конце

## Хэш
Хеширование (от англ. hash, «рубить», «крошить», «мешанина») — это способ преобразовать набор данных и получить их «отпечаток» (англ. fingerprint). Обычно хэш состоит из цифр 0-9 и букв A-F (40 символов для SHA-1).
# Функции хэша
1.если хеш получить дважды для одного и того же набора входных данных, то результат будет гарантированно одинаковый.
2.если хоть что-то в исходных данных поменяется (хотя бы один символ), то хеш тоже изменится (причём сильно).
#Хэш - основной идентификатор коммита