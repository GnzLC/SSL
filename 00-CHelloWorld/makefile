CC = gcc # El compilador a usar
CFLAGS = -Wall -g # Warnings y debug flags

run: hello.exe # Ejecuta el programa y guarda la salida en un archivo
	hello.exe > salida.txt
	type salida.txt

hello.exe: hello.c # Compila el programa
	$(CC) $(CFLAGS) hello.c -o hello.exe
 
clean: # Elimina el ejecutable y el archivo de salida
	del hello.exe salida.txt