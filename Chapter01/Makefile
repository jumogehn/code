
#sdl2-config --cflags
CXXFLAGS=-I/usr/include/SDL2 -D_REENTRANT

#sdl2-config --libs
LDFLAGS=-lSDL2

all:
	g++ -o game Game.cpp Main.cpp $(CXXFLAGS) $(LDFLAGS)

clean:
	rm -rf game test

