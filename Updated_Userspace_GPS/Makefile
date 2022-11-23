CC = arm-linux-gnueabihf-gcc
#TODO: Add Wall and Werror flags
CFLAGS = -static
all: build

clean: 
	rm -f *.o gps_unified *.elf *.map	
build:
	$(CC) $(CFLAGS) -o gps_unified gps_unified.c -lm -Wall