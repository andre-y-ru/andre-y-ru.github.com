HELP
====
Руководство пользователя. Универсальное место для размещения заметок и ссылок с уникальным (авторским) контентом. Здесь пищу только я. Есть желание, что-то написать? Милости прошу. Git - вам поможет!!

Навигация по сайту
------------------
Здесь всё просто. Фото справа, текст слева, заголовок рядом.

Работа с Git
------------
С первого раза непонятно, что за чем. Сейчас поможем!
```bash
1. cd /home/user/andre-y-ru.github.com <!-- переходим в наш репозиторий -->
2. ssh -T git@github.com -i ~/.ssh/key <!-- подключаемся к репозиторию на гитхаб -->
3. git clone git@github.com:andre-y-ru/andre-y-ru.github.com.git <!-- копируем весь репозиторий -->
4. git status <!-- проверяем стату репозитория -->
5. git add index.html <!-- добовляем файл -->
6. git commit -m "мой первый фаил" <!-- пишим комментарий -->
7. git push https://github.com/andre-y-ru/andre-y-ru.github.com.git master <!-- пушим на гитхаб -->
8. git pull https://github.com/andre-y-ru/andre-y-ru.github.com.git master <!-- пулим сайтик на локалку (полезна при работе на нескольких пк) -->
9. git help <!-- помощь? -->
```

Конфигурация с Git!
-------------------
Настройка коммитов, ключа ssh.
```bash
1. git config --global user.name "Firstname Lastname" <!-- логин -->
2. git config --global user.email "email@example.com" <!-- почта -->
3. ssh-keygen -t rsa -C "your_email@youremail.com" <!-- генирация rsa -->
```

Хитрости с Git
--------------
Немного хитростей.
```bash
1. git add a_data/css.css <!-- добовляем фаил из дериктории -->
2. git status <!-- проверяем статус репозитория -->
3. git rm img/icos/\*.ico <!-- удаляем все картинки с расширением .ico -->
4. git rm /img/icos <!-- удаляем папку -->
5. git rm index.html <!-- удаляем фаил -->
```
