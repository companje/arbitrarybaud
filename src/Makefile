# build helloworld executable when user executes "make"
arbitrarybaud: arbitrarybaud.o
	$(CC) $(LDFLAGS) arbitrarybaud.o -o arbitrarybaud
arbitrarybaud.o: arbitrarybaud.c
	$(CC) $(CFLAGS) -c arbitrarybaud.c

# remove object files and executable when user executes "make clean"
clean:
	rm *.o arbitrarybaud


