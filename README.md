## Отчёт по лабораторной работе 1

Заранее установливаю и открываю дистрибутив Linux Ubuntu.

1. Для начала открываю Терминал комбинацией клавиш Ctrl+Alt+T и создаю файл с именем `script.bash` с помощью 'touch'.

![Снимок экрана от 2024-09-17 12-30-21](https://github.com/user-attachments/assets/e01e9f74-79bd-4a39-9aba-7093f60b5c01)


![Снимок экрана от 2024-09-17 12-40-30](https://github.com/user-attachments/assets/3157b4dd-8390-4512-a1cb-e72ff36cf841)

2. Далее в терминале открываю созданный файл `script.bash` для редактирования с помощью 'gedit'.

![Снимок экрана от 2024-09-17 12-45-16](https://github.com/user-attachments/assets/4d7586b7-59df-4661-b6ac-3bb0098e180c)

![Снимок экрана от 2024-09-17 12-45-41](https://github.com/user-attachments/assets/b7eab254-8450-41e6-b932-df776f0fa34b)

3. Далее в файл вписываю следующий скрипт.

```bash
#!/bin/bash (- это путь к исполняемому интерпретатору Bash)

echo "Welcome to ITMO University"
```
![Снимок экрана от 2024-09-17 12-58-21](https://github.com/user-attachments/assets/f7381772-05f2-4dcb-8020-8d347282cea7)


4. Сохраняю файл. Закрываю текстовый редактор `gedit`. Запускаю bash-скрипт, выполнив в терминале:

```bash
bash script.bash
```

![Снимок экрана от 2024-09-17 13-06-56](https://github.com/user-attachments/assets/6ff94092-ed09-4249-a99b-d0b13630fc6a)


5. Та дааам. Теперь, используя все известные мне молитвы, я готова решать следующую задачу. 


### Задача

Модифицируйте файл `script.bash` так, чтобы при его запуске в терминале в виде

```bash
bash script.bash Vasya Pupkin
```

Вывод был

`Welcome, Vasya Pupkin`

*Hint:* Скрипт должен работать для любых имен, даже если это Benedict Timothy Carlton Cumberbatch
