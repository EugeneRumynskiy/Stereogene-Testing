# Stereogene

## Последовательность действий

### 0. Скопирвоать репозиторий, git clone
	git clone https://github.com/favorov/stereogene
**Comment:**  Здесь всё просто. Но, на гитхабе этого нет.

### 1. Создать исполнительынй файл
	After cloning or downloading and unpacking the source, say command ‘make’ from the shell in the source folder. 
	
	cd ../stereogene/src
	make

**Comment:** Это было достаточно сложно найти. Почему этого нет на гитхабе не ясно. Это было в readme в формате .doc (MS Office , это какой год?). Никак не выделено, не обособлено.

**Error:**  

	make[1]: вход в каталог «/mnt/C89CF3A00D398BCA/Users/HOME/Programming/Makeev/stereogene/src»
		make[1]: *** Нет правила для сборки цели «binning.cpp», требуемой для «obj/binning.o».  Останов.
		make[1]: выход из каталога «/mnt/C89CF3A00D398BCA/Users/HOME/Programming/Makeev/stereogene/src»
		Makefile:19: ошибка выполнения рецепта для цели «all»
		make: *** [all] Ошибка 2
