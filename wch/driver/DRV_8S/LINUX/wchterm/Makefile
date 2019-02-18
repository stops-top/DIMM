# Copyright 2009 WCH GROUP all right reserved 
#CC=gcc -fmessage-length=0 -Wall -D_FORTIFY_SOURCE=2 -fstack-protector -O2 -pthread -pipe -o
CC=gcc -Wall -O2 -pthread -pipe -o
 

all: wchterm

install: wchterm
	cp -p wchterm /usr/bin


wchterm: wchterm.c
	$(CC) wchterm wchterm.c -lncurses


clean:  
	rm -f wchterm
	rm -f *~ *.o

