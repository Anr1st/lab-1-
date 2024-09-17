## Лабораторная работа 1

*С чего начинается Linux? С Терминала!!!*

Итак, вы установили дистрибутив Linux Ubuntu (желательно его, но если у вас уже есть другой Linux или вообще MacOS то можно их использовать) и запустили его. Перед вами рабочий стол, панель задач, иконки и прочие вещи - все как и в других ~~менее удобных~~ операционных системах. Предвижу, что вы уже вдоволь наигрались с новым (или нет?) для вас графическим интерфейсом (GUI - graphical user interface) и готовы к самому интересному - знакомству с Терминалом (CLI - command line interface) и выполнению Лабораторной работы №1.

1. Для начала открываю Терминал комбинацией клавиш Ctrl+Alt+T и создаю файл с именем `script.bash`

```bash
touch script.bash
![изображение](https://github.com/user-attachments/assets/3675897e-f4d2-43ab-9773-4db0d5fe33aa)
```

2. Откройте созданный файл `script.bash` для редактирования. Стандартный текстовый редактор в Linux Ubuntu это `gedit`. Выполните в терминале

```bash
gedit script.bash
```

3. Впишите следующий скрипт

```bash
#!/bin/bash

echo "Welcome to ITMO University"
```

4. Сохраните файл. Закройте текстовый редактор `gedit`. Запустите bash-скрипт, выполнив в терминале

```bash
bash script.bash
```

5. Если вы все сделали верно, то в терминале должна отобразиться строка `Welcome to ITMO University`.


А теперь, используя знания полученные из лекций, дополнительных источников и, добавив к этому немного смекалки, решите следующую задачу.

### Задача

Модифицируйте файл `script.bash` так, чтобы при его запуске в терминале в виде

```bash
bash script.bash Vasya Pupkin
```

Вывод был

`Welcome, Vasya Pupkin`

*Hint:* Скрипт должен работать для любых имен, даже если это Benedict Timothy Carlton Cumberbatch.

### Как успешно сдать работу?

Создать свой репозиторий из шаблона этого. Как это делается - "Use this template" -> "Create a new repository" и сделайте его public. 

Находясь уже в своем репозитории - создайте новый файл формата .md и там оформляйте отчет. В отчете опишите все шаги которые вы делали, чтобы получить финальный результат работы. Скриншотов не жалейте, они бесплатные)

Чтобы успешно защитить эту работу у вас должен быть понятный отчет, вы должны понимать базу и основу работы в терминале, какие вообще команды бывают, и знать материал из лекции. Если я вижу что вы понимаете материал, я помогу вам прийти к правильному ответу и это будет плюс вам, если увижу что вы в теме плаваете - нужно было лучше готовиться)))

Что я подразумеваю под основами работы с терминалом, которые вам необходимо знать, чтобы успешно защитить работу:

Как перемещаться по файловой системе; как создать файлы/папки; знать структуру файловой системы в линуксе; как переименовать файлы/папки; как посмотреть справочник; как посмотреть содержимое каталога; как удалять файлы/папки; знать горячие клавиши при работе с терминалом - выполнить последнюю команду, прервать процесс; как копировать и вставлять текст в терминале; как поменять пользователя; какие бывают потоки в терминале; как управлять потоками.

![image](https://github.com/user-attachments/assets/7fa99c40-727f-4437-922c-d596e87a44b3)



### Дополнительные источники

* О системе котроля версий `git`, рекомендуем прочесть разделы 1, 2.1 и 2.2 из [https://git-scm.com/book/ru/v2](https://git-scm.com/book/ru/v2).

* Специальные типы переменных [https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#OTHERTYPESV](https://se.ifmo.ru/~ad/Documentation/ABS_Guide_ru.html#OTHERTYPESV)

* Ресурс, где можно найти ответы на (почти) любые вопросы - https://stackoverflow.com/ и не поверите где еще - https://www.google.ru/

* Хорошая книга по Shell/bash в Linux - "Learn Linux Shell Scripting – Fundamentals of Bash 4.4"  Sebastiaan Tammer
