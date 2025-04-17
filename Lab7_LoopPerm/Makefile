OBJS := syr2k syr2k-perm syr2k-tiled syr2k-ptiled

all: $(OBJS)

syr2k: syr2k.c
	gcc -O3 -o $@ $<

syr2k-perm: syr2k-perm.c
	gcc -O3 -o $@ $<

syr2k-tiled: syr2k-tiled.c
	gcc -O3 -o $@ $<

syr2k-ptiled: syr2k-ptiled.c
	gcc -O3 -o $@ $<

clean:
	rm -rf $(OBJS)
