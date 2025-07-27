CC=gcc
CFLAGS=-Wall -Wextra -std=c11
TARGET=hello-world

all: $(TARGET)

$(TARGET): src/main.c
	$(CC) $(CFLAGS) -o $(TARGET) src/main.c

clean:
	rm -f $(TARGET)