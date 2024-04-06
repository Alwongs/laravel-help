## Решение проблемы со звуком в Yandex browser
- скачать файл установки браузера с расширением .deb с официального источника
- выполнить команду:  
&nbsp;&nbsp;&nbsp;&nbsp;    sudo dpkg -i ~/Загрузки/Yandex*.deb
- если ошибка, выполнить команду:  
&nbsp;&nbsp;&nbsp;&nbsp;    sudo apt install -f


## Создание загрузочной флешки
Сначала вам нужно узнать имя вашей флешки в файловой системе. Для этого используйте утилиту fdisk:  
&nbsp;&nbsp;&nbsp;&nbsp;    $ sudo fdisk -l  
&nbsp;&nbsp;&nbsp;&nbsp;    {*  тут должен быть пример *}  
В данном примере флешка имеет имя /dev/sdb.  

Теперь можно записать на неё образ:  
&nbsp;&nbsp;&nbsp;&nbsp;    $ sudo dd if=~/Загрузки/ubuntu20_04.iso of=/dev/sdb bs=1M  


## Установка ОС Ubuntu 22.04
&nbsp;&nbsp;&nbsp;&nbsp;    https://www.youtube.com/watch?v=e2uv6TKzxmk&t=88s
