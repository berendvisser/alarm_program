BASE = /home/pi/Programming/C/alarm_program
CC = gcc
CFLAGS = -O -Wall
EFILE = $(BASE)/bin/executable
INCLS = -I$(BASE)/include
OBJS = main.o

$(EFILE) : main.o
	@echo "linking.." 
	@$(CC) $(CFLAGS) -o $(EFILE) $(OBJS)
main.o : main.c
	@echo "compiling..." 
	$(CC) $(CFLAGS) $(INCLS) -c $*.c
