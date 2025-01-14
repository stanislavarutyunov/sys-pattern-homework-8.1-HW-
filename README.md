# Домашнее задание к занятию "8.1. Git" - Арутюнов Станислав
## Инструкция по выполнению домашнего задания
##### 1.Сделайте fork репозитория c Шаблоном решения к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/gitlab-hw или https://github.com/имя-вашего-репозитория/8-03-hw).
2.Выполните клонирование данного репозитория к себе на ПК с помощью команды git clone.

3.Выполните домашнее задание и заполните у себя локально этот файл README.md:

- впишите вверху название занятия и вашу фамилию и имя
- в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
- для корректного добавления скриншотов воспользуйтесь инструкцией "Как вставить скриншот в шаблон с решением"
- при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в инструкции по MarkDown)

4.После завершения работы над домашним заданием сделайте коммит (git commit -m "comment") и отправьте его на Github (git push origin);

5.Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.

6.Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.

Желаем успехов в выполнении домашнего задания!



## Задание 1. 
```
 1.Зарегистрируйте аккаунт на https://github.com/.
 2.Создайте публичный репозиторий. Обязательно поставьте галочку Initialize this repository with a README.
 3.Склонируйте репозиторий, используя https протокол (git clone ...).
 4.Перейдите в каталог с клоном репозитория.
 5.Произведите первоначальную настройку git, указав свое настоящее имя и email (git config --global user.name и git config --global user.email johndoe@example.com).
 6.Выполните команду git status и запомните результат.
 7.Отредактируйте файл README.md любым удобным способом, тем самым переведя файл в состояние Modified.
 8.Еще раз выполните git status и продолжайте проверять вывод этой команды после каждого последующего шага.
 9.Давайте теперь посмотрим изменения в файле README.md, выполнив команды git diff и git diff --staged.
 10.Переведите файл в состояние staged (или как говорят просто добавьте файл в коммит) командой git add README.md.
 11.И еще раз выполните команды git diff и git diff --staged.
 12.Теперь можно сделать коммит git commit -m 'First commit'.
 13.Сделайте git push origin master.

 В качестве ответа на задание добавьте ссылку на этот коммит в ваш md-файл с решением
 
Решение: https://github.com/stanislavarutyunov/homeworksys15/commit/b763aea9eb8ca0d3b028974f328b16e845430f3b
 
```
## Задание 2.
```
1.Создайте файл .gitignore (обратите внимание на точку в начале файла), проверьте его статус сразу после создания.
2.Добавьте файл .gitignore в следующий коммит (git add...).
3.Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
4.Сделайте коммит и пуш.

 В качестве ответа на задание добавьте ссылку на этот коммит в ваш md-файл с решением
 
 Решение: https://github.com/stanislavarutyunov/homeworksys15/commit/d93a81cde9805cdd94b983337f84657bb176af89 
```
## Задание 3.
```
1.Создайте новую ветку dev и переключитесь на нее.
2.Создайте файл test.sh с произвольным содержимым.
3.Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
4.Сделайте мердж данной ветки в основную (для начала необходимо переключиться на нее, и потом вызывать git merge).
5.Сделайте коммит и пуш.

В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ВАШ_ЛОГИН/ВАШ_РЕПОЗИТОРИЙ/network в ваш md-файл с решением
```
Решение: https://github.com/stanislavarutyunov/homeworksys15/network
