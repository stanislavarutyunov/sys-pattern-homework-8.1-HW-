
       Домашнее задание к занятию "8.1 Git" - Арутюнов Станислав
Инструкция по выполнению домашнего задания
Сделайте fork данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
Выполните клонирование данного репозитория к себе на ПК с помощью команды git clone.
Выполните домашнее задание и заполните у себя локально этот файл README.md:
впишите вверху название занятия и вашу фамилию и имя
в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
для корректного добавления скриншотов воспользуйтесь инструкцией "Как вставить скриншот в шаблон с решением
при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в инструкции по MarkDown)
После завершения работы над домашним заданием сделайте коммит (git commit -m "comment") и отправьте его на Github (git push origin);
Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
Желаем успехов в выполнении домашнего задания!

Дополнительные материалы, которые могут быть полезны для выполнения задания
Руководство по оформлению Markdown файлов








Задание 1.

Зарегистрируйте аккаунт на https://github.com/.
Создайте публичный репозиторий. Обязательно поставьте галочку Initialize this repository with a README.
Склонируйте репозиторий, используя https протокол (git clone ...).
Перейдите в каталог с клоном репозитория.
Произведите первоначальную настройку git, указав свое настоящее имя и email (git config --global user.name и git config --global user.email johndoe@example.com).
Выполните команду git status и запомните результат.
Отредактируйте файл README.md любым удобным способом, тем самым переведя файл в состояние Modified.
Еще раз выполните git status и продолжайте проверять вывод этой команды после каждого последующего шага.
Давайте теперь посмотрим изменения в файле README.md, выполнив команды git diff и git diff --staged.
Переведите файл в состояние staged (или как говорят просто добавьте файл в коммит) командой git add README.md.
И еще раз выполните команды git diff и git diff --staged.
Теперь можно сделать коммит git commit -m 'First commit'.
Сделайте git push origin master.
В качестве ответа на задание добавьте ссылку на этот коммит в ваш md-файл с решением






===============================================================================


Задание 2.
Создайте файл .gitignore (обратите внимание на точку в начале файла), проверьте его статус сразу после создания.
Добавьте файл .gitignore в следующий коммит (git add...).
Напишите правила в этом файле, чтобы игнорировать любые файлы .pyc, а также все файлы в директории cache.
Сделайте коммит и пуш.
В качестве ответа на задание добавьте ссылку на этот коммит в ваш md-файл с решением





===============================================================================


Задание 3.
Создайте новую ветку dev и переключитесь на нее.
Создайте файл test.sh с произвольным содержимым.
Сделайте несколько коммитов и пушей, имитируя активную работу над этим файлом.
Сделайте мердж данной ветки в основную (для начала необходимо переключиться на нее, и потом вызывать git merge).
Сделайте коммит и пуш.
В качестве ответа на задание прикрепите ссылку на граф коммитов https://github.com/ВАШ_ЛОГИН/ВАШ_РЕПОЗИТОРИЙ/network в ваш md-файл с решением




