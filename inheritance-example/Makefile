
CXXFLAGS = -Lgtest
LDFLAGS = -lgtest -lgtest_main -std=c++11

BINARIES=hello-world

all: $(BINARIES)

$(NAME): $(NAME).o
	${CXX} ${LDFLAGS} $(NAME).o -o $(NAME) 

clean:
	/bin/rm -f *.o $(BINARIES)


