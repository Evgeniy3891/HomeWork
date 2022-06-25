# Задание со *

1) Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request

___
    curl http://162.55.220.72:5005/terminal-hw-request

[результат](https://github.com/Evgeniy3891/HomeWork/blob/main/first_request.png) 

___

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13


___

    #!/bin/bash
    cd HW1
    mkdir one two three
    cd one
    touch a.txt b.txt c.txt A.json B.json
    mkdir aaa bbb ccc
    ls -la
    mv a.txt b.txt aaa/

[результат](https://github.com/Evgeniy3891/HomeWork/blob/main/script.png)

