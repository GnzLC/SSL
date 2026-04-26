CC = gcc
CFLAGS = -Wall -g

run: hello.exe
	hello.exe > salida.txt
	type salida.txt

hello.exe: hello.c
	$(CC) $(CFLAGS) hello.c -o hello.exe

clean:
	del hello.exe salida.txt