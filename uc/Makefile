CFLAGS  = -Wall

all:
	@echo "Which language?"

c: uc.c
	gcc $(CFLAGS) $^ -o uc

haskell: uc.hs
	ghc $(CFLAGS) --make uc

python: uc.py
	cp $^ uc
	chmod 755 uc

make clean:
	rm -f *.o *.hi uc
