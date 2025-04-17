OBJS := syr2k syr2k-perm

all: $(OBJS)

syr2k: syr2k.c
	gcc -O3 -o $@ $<

syr2k-perm: syr2k-perm.c
	gcc -O3 -o $@ $<

clean:
	rm -rf $(OBJS)
