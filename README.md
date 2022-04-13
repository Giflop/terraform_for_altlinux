# terraform_for_altlinux
altlinux

1. Перенесем файл:
	$ mv /ваш_локальный_путь_до_файла/terraform /usr/local/bin/
2. Прописываем путь в .bash_progile:
	echo 'export PATH=/usr/local/bin:$PATH' >>~/.bash_profile
3. Запускаем установку порседством скрипта:
	bash terraform.sh

