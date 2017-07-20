TARGET = a.out
CC = gcc
OBJS = fork.o
CFLAGS = -Wall  -c -g -DDEBUG

${TARGET}: ${OBJS}
	${CC} -o $@ $^

.c.o:
	${CC} ${CFLAGS} $*.c 

clean:
	-rm -f ${TARGET} ${OBJS}