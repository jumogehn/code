
#sdl2-config --cflags
CXXFLAGS=-I/usr/include/SDL2 -D_REENTRANT

#sdl2-config --libs
LDFLAGS=-L/usr/lib/x86_64-linux-gnu -lSDL2 -lSDL2_image

SRC=SpriteComponent.cpp \
    Ship.cpp Math.cpp \
    Component.cpp \
    BGSpriteComponent.cpp \
    AnimSpriteComponent.cpp \
    Actor.cpp \
    Game.cpp \
    Main.cpp

BIN=game
OUTPUT=-o $(BIN)

all:
	g++ $(OUTPUT) $(SRC) $(CXXFLAGS) $(LDFLAGS)

clean:
	rm -rf $(BIN)

