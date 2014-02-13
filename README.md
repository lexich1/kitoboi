kitoboi
=======
## Инициализируем репозиторий:
1. Нажать кнопку Fork
2. Скопировать адрес форка https://github.com/AlexXoxol/kitoboi
3. На диска создать папку для проекта
4. ПКМ -> Git Bash
5. $ git init
6. $ git remote add kit https://github.com/AlexXoxol/kitoboi

## Вносим изменения в проект:
7. $ git fetch kit
8. $ git pull kit master
9. $ git checkout -b K-2

## Редактируем файлы, после:
$ git status - посмотреть что изменилось
$ git add README.md - добавляем измененные файлы
$ git commit -b 'K-2. Message' - коммитим в локальный репозиторий изменения

## Когда таска готова:
10. $ git push kit K-2
11. Идем на страницу своего форка https://github.com/AlexXoxol/kitoboi
12. Жмем кнопку Compare & pull request
13. Send pull request