CC=gcc
CFLAGS=-Wall -I./include
SRC=src/Hello.c  # Path to your source file
OBJ=$(SRC:.c=.o)
EXE=hello

all: $(EXE)

$(EXE): $(OBJ)
    $(CC) $(OBJ) -o $(EXE)

clean:
    rm -f $(OBJ) $(EXE)
