CC=gcc
CFLAG=-Wall -g

SRC=$(wildcard *.c)
OBJ=$(SRC:.c=.o)

TARGET=test

all:$(TARGET)
	@echo program has been compiled!

$(TARGET):$(OBJ)
	$(CC) $(CFLAG) -o $(TARGET) $(OBJ)

clean:
	rm -rf *.o