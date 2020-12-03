CC = gcc
CFLAGS = -W -Wall -O2 -g
CPPFLAGS = -I.
LDLIBS = -lz
PROGS = mkcramfs cramfsck

all: $(PROGS)

install: $(PROGS)
	cp $(PROGS) /usr/local/bin/

distclean clean:
	rm -f $(PROGS)

.PHONY: all clean
