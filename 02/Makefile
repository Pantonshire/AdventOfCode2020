HS_MAIN = main.hs
HS_EXEC = 02

haskell:
	ghc -o $(HS_EXEC) $(HS_MAIN)

clean:
	rm $(HS_EXEC) *.hi *.o

.PHONY: haskell clean