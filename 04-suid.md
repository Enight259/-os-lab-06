Вывод ls -l /usr/bin/passwd (SUID это буква s)
<img width="1171" height="263" alt="image" src="https://github.com/user-attachments/assets/51240c7f-9619-4698-95d0-e18ae18299cf" />

Вывод ls -l ~/demobash и id 
<img width="1708" height="257" alt="image" src="https://github.com/user-attachments/assets/e847a77d-74d1-431b-9910-73be14163ede" />

~~~
Вопрос 1:
euid=0 означает, что в данный момент программа действует от имени root (0). Он появился 
~~~

~~~
Вопрос 2:
/etc/shadow защищен так, что изменять его может только root. Мы не являмся рутом по этому не можем его изменять, а Процесс SUID мщжет тк запущен от имени root.
~~~
