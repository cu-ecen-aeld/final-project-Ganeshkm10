all: gps
CC		= aarch64-none-linux-gnu-
CFLAGS	= -std=c11 -O0 -Wall -g
OBJS	= gps.o
LIBS	= -lgps -lm

gps: $(OBJS)
	$(CC) -o $< $(OBJS) $(LIBS)
gps.o: gps.c
	$(CC) -c $< $(CFLAGS)

clean:
	-@rm -f *.o gps
