# Laba6_Boot_OS
<h3>Configuring grub2</h3>

1. Выполнен вход в систему Linux CentOS без пароля 3 методами (описано в <b>Booting</b>): 

<p>a)  init=/bin/sh </p>
<p>b)  rd.break </p>
<p>c)  init=/sysroot/bin/sh </p>

2. Установлена система с LVM, переменована VG: 
3. Добавлен модуль со скриптами в initrd. 

<p>Файл <b>Logging</b> - лог действий. </p>
<p><b>fstab, grub, grub.cfg</b> - файлы для загрузки с новыми VG </p>

<p>Скрипты </p>
<p><b>module-setup.sh</b> - установка модуля и вызов скрипта test.sh</p>
<p><b>test.sh</b> - рисует пингвина при загрузке и ждет 10 сек</p>
