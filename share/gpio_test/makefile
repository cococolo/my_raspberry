CC=g++
CFLAG=-Wall -g

SRC=$(wildcard *.cpp)
OBJ=$(SRC:.c=.o)

TARGET=test

all:$(TARGET)
	@echo program has been compiled!

$(TARGET):$(OBJ)
	$(CC) $(CFLAG) -o $(TARGET) $(OBJ)

clean:
	rm -rf *.o