# **************************************************************************** #
#                                                                              #
#                                                         :::      ::::::::    #
#    Makefile                                           :+:      :+:    :+:    #
#                                                     +:+ +:+         +:+      #
#    By: flcarre <flcarre@student.42.fr>            +#+  +:+       +#+         #
#                                                 +#+#+#+#+#+   +#+            #
#    Created: 2018/08/23 16:03:09 by flcarre           #+#    #+#              #
#    Updated: 2018/08/23 21:30:05 by flcarre          ###   ########.fr        #
#                                                                              #
# **************************************************************************** #
LIB = libft.a
SRCS	=	srcs/*.c
HEADERS = ./includes
OBJ	=	*.o

CC	=	gcc

CFLAGS	=	-Wall -Wextra -Werror

RM	=	rm -rf

all	: $(LIB)

$(LIB):
	ar rc $(LIB) $(OBJ)
	ranlib $(LIB)

obj:
	$(CC) $(CFLAGS) -c $(SRCS) -I $(HEADERS)

clean:
	rm -rf $(OBJ)

fclean: clean
	rm -rf $(LIB)

re: fclean all
