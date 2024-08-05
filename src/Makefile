#sudo apt install libcglm-dev
#sudo apt install libglfw3 libglfw3-dev
#sudo apt install libglew-dev

LD=-lcglm -lGL -lGLEW -lglfw -lm

all:
	rm -f main
	gcc main.c $(LD) -o main
	./main