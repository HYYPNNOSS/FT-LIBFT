## 🗣️ About

> _The aim of this project is to code a C library regrouping usual functions that you'll be allowed to use in all your other projects._

### Functions from `<ctype.h>` library

* [`ft_isascii`](libft/ft_isascii.c)			- test for ASCII character.
* [`ft_isalnum`](libft/ft_isalnum.c)			- alphanumeric character test.
* [`ft_isalpha`](libft/ft_isalpha.c)			- alphabetic character test.
* [`ft_islower`](libft/ft_islower.c) *	- lower-case character test.
* [`ft_isupper`](libft/ft_isupper.c) *	- upper-case character test.
* [`ft_isdigit`](libft/ft_isdigit.c)			- decimal-digit character test.
* [`ft_isprint`](libft/ft_isprint.c)			- printing character test (space character inclusive).
* [`ft_isspace`](libft/ft_isspace.c) *	- white-space character test.
* [`ft_tolower`](libft/ft_tolower.c)			- upper case to lower case letter conversion.
* [`ft_toupper`](libft/ft_toupper.c)			- lower case to upper case letter c

### Functions from `<stdlib.h>` library

* [`ft_atoi`](libft/ft_atoi.c)		- convert ASCII string to integer.
* [`ft_atof`](libft/ft_atof.c) *		- convert ASCII string to integer.
* [`ft_calloc`](libft/ft_calloc.c)	- memory allocation.

### Functions from `<strings.h>` library

* [`ft_bzero`](libft/ft_bzero.c)		- write zeroes to a byte string.
* [`ft_memset`](libft/ft_memset.c)		- write a byte to a byte string.
* [`ft_memchr`](libft/ft_memchr.c)		- locate byte in byte string.
* [`ft_memcmp`](libft/ft_memcmp.c)		- compare byte string.
* [`ft_memmove`](libft/ft_memmove.c)	- copy byte string.
* [`ft_memcpy`](libft/ft_memcpy.c)		- copy memory area.
* [`ft_memccpy`](libft/ft_memccpy.c)	- copy string until character found.


### Functions from `<string.h>` library

* [`ft_strlen`](libft/ft_strlen.c)				- find length of string.
* [`ft_strchr`](libft/ft_strchr.c)				- locate character in string (first occurrence).
* [`ft_strrchr`](libft/ft_strrchr.c)			- locate character in string (last occurence).
* [`ft_strcmp`](libft/ft_strcmp.c) *		- compare strings.
* [`ft_strncmp`](libft/ft_strncmp.c) *			- compare strings (size-bounded).
* [`ft_strcpy`](libft/ft_strcpy.c) *		- copy strings.
* [`ft_strdup`](libft/ft_strdup.c)				- save a copy of a string (with malloc).
* [`ft_strcat`](libft/ft_strcat.c) *		- concatenate strings (s2 into s1).
* [`ft_strncat`](libft/ft_strncat.c) *	- concatenate strings (s2 into s1, size-bounded).
* [`ft_strlcpy`](libft/ft_strlcpy.c)			- size-bounded string copying.
* [`ft_strlcat`](libft/ft_strlcat.c)			- size-bounded string concatenation.

### Non-standard functions

* [`ft_swap`](libft/ft_swap.c) *			- swap value of two integers.
* [`ft_putchar`](libft/ft_putchar.c) *	- output a character to stdout.
* [`ft_putchar_fd`](libft/ft_putchar_fd.c)		- output a character to given file.
* [`ft_putstr`](libft/ft_putstr.c) *		- output string to stdout.
* [`ft_putstr_fd`](libft/ft_putstr_fd.c)		- output string to given file.
* [`ft_putendl_fd`](libft/ft_putendl_fd.c)		- output string to given file with newline.
* [`ft_putnbr`](libft/ft_putnbr.c) *		- output integer to stdout.
* [`ft_putnbr_fd`](libft/ft_putnbr_fd.c)		- output integer to given file.
* [`ft_itoa`](libft/ft_itoa.c)					- convert integer to ASCII string.
* [`ft_substr`](libft/ft_substr.c)				- extract substring from string.
* [`ft_strtrim`](libft/ft_strtrim.c)			- trim beginning and end of string with the specified characters.
* [`ft_strjoin`](libft/ft_strjoin.c)			- concatenate two strings into a new string (with malloc).
* [`ft_split`](libft/ft_split.c)				- split string, with specified character as delimiter, into an array of strings.
* [`ft_strmapi`](libft/ft_strmapi.c)			- create new string from modifying string with specified function.
