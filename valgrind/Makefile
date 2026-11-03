CC = gcc
CFLAGS = -g -Wall -lm
bin = trials
src = trials.c

disassembly: ${bin}
	objdump -d $^ > $@

${bin}: ${src}
	${CC} ${CFLAGS} $^ -o $@

clean:
	rm -f ${bin} disassembly
