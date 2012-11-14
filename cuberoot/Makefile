LDLIBS=-lm -lglut -lGL -lGLEW -std=c++0x
CXXFLAGS=-O6 -ffast-math -Wall
all: cuberoot
clean:
	rm -f *.o cuberoot
cuberoot: ../common/shader_utils.o
.PHONY: all clean
