.PHONY: all clean install

all: helloworld

clean:
	rm -f helloworld

helloworld: helloworld.c
	gcc -Wall -g helloworld.c -o helloworld

install:
	mkdir -p $(DESTDIR)/usr/bin
	cp helloworld $(DESTDIR)/usr/bin/helloworld
