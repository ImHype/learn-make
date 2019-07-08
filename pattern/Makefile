all:$(subst .c,.o,$(wildcard *.c))

# %.o -> $@
# %.c -> $<
%.o:%.c
	gcc -o $@ $<