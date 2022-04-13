# terraform_for_altlinux
altlinux

1. Распоковать архив
2. Перенесем файл:
	$ mv /ваш_локальный_путь_до_файла/terraform /usr/local/bin/
3. Прописываем путь в .bash_progile:
	echo 'export PATH=/usr/local/bin:$PATH' >>~/.bash_profile
4. Запускаем установку порседством скрипта:
	bash terraform.sh

