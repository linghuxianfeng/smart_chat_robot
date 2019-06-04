gcc -o obj/voice.o -Iinclude -c src/voice.c
gcc -o bin/test -Iinclude obj/libmsc.so obj/voice.o src/main.c -lpthread -lwiringPi -lrt -ldl -lpthread 
 sudo ./bin/test
 
