
CC = gcc
CFLAGS = -O3 -Wall -fno-delete-null-pointer-checks

all: fpkg

fpkg: fpkg.c
	$(CC) $(CFLAGS) -o $@ $^

dcfg: dcfg.c
	$(CC) $(CFLAGS) -o $@ $^

clean:
	rm -f *.o fpkg dcfg

%.o: %.c
	$(CC) $(CFLAGS) -c $<
