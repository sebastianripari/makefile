# Usage:
# make        # compile all binary
# make clean  # remove ALL binaries and objects

.PHONY = all clean

CC = gcc                        # compiler to use

LINKERFLAG = -lm

# Esta es la forma de indicar que
# en source van todos los archivos
# que terminan con la extension '.c'.
SRCS := $(wildcard *.c)
BINS := $(SRCS:%.c=%)

all: ${BINS}

%: %.o
	@echo "Checking.."
	${CC} ${LINKERFLAG} $< -o $@

# Agarra cada archivo '.c' y lo compila,
# generando el '.o' correspondiente.
# Ejemplo: 'hola.c' -> 'hola.o'.
%.o: %.c
	@echo "Creating object.."
	${CC} -c $<

clean:
	@echo "Cleaning up..."
	rm -rvf *.o ${BINS}