
all: build

debug: clean
	cabal configure --disable-library-profiling --enable-executable-dynamic --disable-optimization --ghc-options="-Wall"

clean:
	cabal clean

build:
	cabal build -j
	cabal haddock --hyperlink-sources
