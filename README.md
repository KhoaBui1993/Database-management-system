# Database-management-system

Using follow commands to run hw1.sqc:
a.	db2 prep h1.sqc

b.	gcc -I./sqllib/include -c h1.c

c.	gcc -o h1 h1.o -L./sqllib/lib  -ldb2

d.	./h1 h1

