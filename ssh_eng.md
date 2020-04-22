Creating ssh key
------------------

You will need ssh key to connect to VMs.

You can create it using freeware **putty** utility as described below.

1.  Open <https://putty.org>

![](media/ssh/image1.png)

2.  Download **putty** installation.

![](media/ssh/image2.png)

3.  Install **putty** to your computer (you will need administrator rights).
    для установки. Если их нет, то вы можете скачать исполняемые файлы
    exe **putty** и **puttygen в локальную папку**).

4.  Запустите **puttygen** и нажмите кнопку **Generate**.

![](media/ssh/image3.png)

5.  Следуйте инструкциям, чтобы сгенерировать ключ. Двигайте мышью
    некоторое время.

6.  Сохраните приватный ключ (для практикума вы можете не задавать
    пароль для ключа).

7.  Для доступа к виртуальным машинам публичный ключ находится в
    текстовом блоке в окне **puttygen**:

![](media/ssh/image4.png)

8.  Не закрывайте это окно, т.к. публичный ключ нам потребуется позже.

Подключение к виртуальной машине через ssh
------------------------------------------

1.  Запустите **Putty**.

![](media/ssh/image5.png)

2.  Введите Публичный IP-адрес вашей виртуальной машины и имя сохраняемой сессии (например, workshop) и нажмите кнопку **Save**:

![](media/ssh/image6.png)

3.  Перейдите в пункт **Connection / SSH / Auth** и откройте сохраненный
    ранее **Приватный** ключ, нажав кнопку Browse:

![](media/ssh/image7.png)

4.  Перейдите в пункт **Connection / Data** и введите в поле
    **Auto-login username**: **opc (для Oracle Linux)**

![](media/ssh/image8.png)

5.  Перейдите в пункт **Connection** и установите интервал keepalive в
    60 секунд, чтобы соединение не прерывалось по неактивности:

![](media/ssh/image9.png)

6.  Вернитесь в пункт **Session** и нажмите **Save** еще раз.

![](media/ssh/image6.png)

7.  Нажмите **Open**, чтобы подключиться к виртуальной машине.

8.  Вы увидите предупреждение (только в первый раз). Нажмите **Yes**.

![](media/ssh/image10.png)