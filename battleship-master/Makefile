bship: main.o Executive.o Board.o Player.o Ship.o
	g++ -g -Wall -std=c++11 main.o Executive.o Board.o Player.o Ship.o -o bship

main.o: main.cpp
	g++ -g -Wall -std=c++11 -c main.cpp

Executive.o: Executive.cpp Executive.h
	g++ -g -Wall -std=c++11 -c Executive.cpp

Player.o: Player.cpp Player.h
	g++ -g -Wall -std=c++11 -c Player.cpp

Board.o: Board.cpp Board.h
	g++ -g -Wall -std=c++11 -c Board.cpp

Ship.o: Ship.cpp Ship.h
	g++ -g -Wall -std=c++11 -c Ship.cpp
	
clean:
	rm *.o bship

