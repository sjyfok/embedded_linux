CC=arm-linux-gcc
EXEC=hello
OBJS=hello.o
CFLAGS+=
LDFLAGS+=-static

ALL:$(EXEC)
$(EXEC):$(OBJS)
	$(CC) $(LDFLAGS) -o $@ $(OBJS)
clean:
	-rm -f $(EXEC) *.elf *.o *.gdb

