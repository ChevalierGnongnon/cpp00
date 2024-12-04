NAME = megaphone

SOURCES = megaphone.cpp

OBJS = $(SOURCES:.cpp=.o)

RM = rm -rf 

CC = g++

FLAGS = -Werror -Wextra -Wall -std=c++98

all: $(NAME)

$(NAME):$(OBJS)
	$(CC) $(FLAGS) $(OBJS) -o $(NAME)

clean:
	$(RM) $(OBJS)

fclean: clean
	$(RM) $(NAME)

re: fclean $(NAME)

.PHONY: all clean fclean re