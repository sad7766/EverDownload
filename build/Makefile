# Compiler
CC = gcc

# Compiler flags
CFLAGS = -Wall -Wextra -O2

# Source files
SOURCES = main.c

# Executable name
EXECUTABLE = program

# Default target
all: run

# Build target
build: $(SOURCES)
	$(CC) $(CFLAGS) -o $(EXECUTABLE) $(SOURCES)

# Run target
run: build
	./$(EXECUTABLE)
	$(MAKE) clean

# Clean target
clean:
	rm -f $(EXECUTABLE)

# Phony targets
.PHONY: all build run clean
