CFLAGS = -Wall -Wno-write-strings -g

all:
	$(CC) $(CFLAGS) $(LDFLAGS) speedtest-cli.c -o speedtest-cli -lm -lpthread

clean:
	rm -f *.o speedtest-cli
