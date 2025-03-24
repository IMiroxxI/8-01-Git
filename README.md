# Домашнее задание к занятию "`Git`" - `Khalatov Alexandr`

### Задание 1

1. Зарегистрируйте аккаунт на GitHub.
![1](https://github.com/IMiroxxI/8-01-Git/blob/main/img/1.jpg)
2. Создайте новый отдельный публичный репозиторий. Обязательно поставьте галочку в поле «Initialize this repository with a README». 
![2](https://github.com/IMiroxxI/8-01-Git/blob/main/img/2.png)
3. Склонируйте репозиторий, используя https протокол `git clone ...`.
![3](https://github.com/IMiroxxI/8-01-Git/blob/main/img/3.png)
4. Перейдите в каталог с клоном репозитория.
![4](https://github.com/IMiroxxI/8-01-Git/blob/main/img/4.png)
5. Произведите первоначальную настройку Git, указав своё настоящее имя и email: `git config --global user.name` и `git config --global user.email johndoe@example.com`.
![5](https://github.com/IMiroxxI/8-01-Git/blob/main/img/5.png)
6. Выполните команду `git status` и запомните результат.
![6](https://github.com/IMiroxxI/8-01-Git/blob/main/img/6.png)
7. Отредактируйте файл README.md любым удобным способом, переведя файл в состояние Modified.
![7](https://github.com/IMiroxxI/8-01-Git/blob/main/img/7.png)
8. Ещё раз выполните `git status` и продолжайте проверять вывод этой команды после каждого следующего шага.
![8](https://github.com/IMiroxxI/8-01-Git/blob/main/img/8.png)
9. Посмотрите изменения в файле README.md, выполнив команды `git diff` и `git diff --staged`.
![9](https://github.com/IMiroxxI/8-01-Git/blob/main/img/9.png)
10. Переведите файл в состояние staged или, как говорят, добавьте файл в коммит, командой `git add README.md`.
![10](https://github.com/IMiroxxI/8-01-Git/blob/main/img/10.png)
11. Ещё раз выполните команды `git diff` и `git diff --staged`.
![11](https://github.com/IMiroxxI/8-01-Git/blob/main/img/11.png)
12. Теперь можно сделать коммит `git commit -m 'First commit'`.
![12](https://github.com/IMiroxxI/8-01-Git/blob/main/img/12.png)
13. Сделайте `git push origin master`.
![13](https://github.com/IMiroxxI/8-01-Git/blob/main/img/13.png)

[Ссылка на коммит](https://github.com/IMiroxxI/8-01/commit/e48295ba022506e6fa38208c7c0ecf30395a9596)
---

### Задание 2

1. Создайте файл .gitignore (обратите внимание на точку в начале файла) и проверьте его статус сразу после создания.
![1](https://github.com/IMiroxxI/8-01-Git/blob/main/img2/2-1.png)
2. Добавьте файл .gitignore в следующий коммит `git add...`.
![2](https://github.com/IMiroxxI/8-01-Git/blob/main/img2/2-2.png)
3. Напишите правила в этом файле, чтобы игнорировать любые файлы `.pyc`, а также все файлы в директории `cache`.
![3](https://github.com/IMiroxxI/8-01-Git/blob/main/img2/2-3.png)
4. Сделайте коммит и пуш.
![4](https://github.com/IMiroxxI/8-01-Git/blob/main/img2/2-4.png)

[Ссылка на коммит](https://github.com/IMiroxxI/8-01/commit/6c18153fbc2cbc345a05712e3b501ab5d65a2392)

---

### Задание 3

1. Создайте новую ветку dev и переключитесь на неё.
![1](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-1.png)
2. Создайте в ветке dev файл test.sh с произвольным содержимым.
![2](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-2.png)
![2.1](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-2.1.png)
3. Сделайте несколько коммитов и пушей  в ветку dev, имитируя активную работу над  файлом в процессе разработки.
![3](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-2.2.png)
![3.1](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-2.3.png)
4. Переключитесь на основную ветку.
![4](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-4.png)
5. Добавьте файл main.sh в основной ветке с произвольным содержимым, сделайте комит и пуш . Так имитируется продолжение общекомандной разработки в основной ветке во время разработки отдельного функционала в dev  ветке.
![5](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-5.png)
![5.1](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-5.1.png)
6. Сделайте мердж dev  ветки в основную с помощью git merge dev. Напишите осмысленное сообщение в появившееся окно комита.
![6](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-6.png)
7. Сделайте пуш в основной ветке.
![7](https://github.com/IMiroxxI/8-01-Git/blob/main/img3/3-7.png)
8. Не удаляйте ветку dev.

[Ссылка на граф коммитов](https://github.com/IMiroxxI/8-01/network)
---
