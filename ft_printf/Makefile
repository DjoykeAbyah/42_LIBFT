# **************************************************************************** #
#                                                                              #
#                                                         ::::::::             #
#    Makefile                                           :+:    :+:             #
#                                                      +:+                     #
#    By: dreijans <dreijans@student.codam.nl>         +#+                      #
#                                                    +#+                       #
#    Created: 2022/11/15 18:56:16 by dreijans      #+#    #+#                  #
#    Updated: 2023/03/23 15:35:39 by dreijans      ########   odam.nl          #
#                                                                              #
# **************************************************************************** #

NAME = printf.a
CC = cc
SRC = \
ft_printf.c \
print_char.c \
print_nbr.c \
print_hexlow.c \
print_hexup.c \
print_str.c \
print_unsigned.c \
print_ptr.c 
OBJ_FILES = $(SRC:.c=.o)
CFLAGS = -Wall -Wextra -Werror

.PHONY: all clear fclean re

all: $(NAME)
	
$(NAME): $(OBJ_FILES) 
		ar -src $(NAME) $(OBJ_FILES)

%.o: %.c
		@$(CC) -c $(CFLAGS) -o $@ $^

clean:
		rm -f $(OBJ_FILES)

fclean: clean
		rm -f $(NAME)

re: fclean all
