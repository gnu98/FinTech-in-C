CC = gcc
CFLAGS = -g
LDFLAGS = -lm
#VPATH = src
#vpath %.h include

.PHONY: clean

%: %.c
	${CC} $(CFLAGS) $(LDFLAGS) -o $@ $^

