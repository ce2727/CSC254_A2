# Trivial makefile for the calculator scanner/parser.
# Depends on default (built-in) rules for C compilation.

CXXFLAGS = -std=c++11
# Note that rule for goal (parse) must be the first one in this file.

parse: parse.o scan.o
	g++ $(CXXFLAGS) -o parse parse.o scan.o

clean:
	rm *.o parse

parse.o: scan.h
scan.o: scan.h
