CC = gcc
OBJS = main.o
TARGET = out

.PHONY:
	all clean
all:$(TARGET)

$(TARGET):main.o
	$(CC) -o $(TARGET) main.o
clean:
	$(RM) $(OBJS) $(TARGET)
main.o:main.c
	$(CC) -c main.c
