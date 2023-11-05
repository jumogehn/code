
CXXFLAGS=-I/opt/sdl2/include/SDL2 -D_REENTRANT
LDFLAGS=-L/opt/sdl2/lib -Wl,-rpath,/opt/sdl2/lib -Wl,--enable-new-dtags -lSDL2

all:
	g++ -o game Game.cpp Main.cpp $(CXXFLAGS) $(LDFLAGS)
clean:
	rm -rf game

