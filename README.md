## 🗣️ About

> _The aim of this project is to code a C library regrouping usual functions that you'll be allowed to use in all your other projects._

### Functions from `<ctype.h>` library

* [`ft_isascii`](ft_libft/ft_isascii.c)			- test for ASCII character.
* [`ft_isalnum`](ft_libft/ft_isalnum.c)			- alphanumeric character test.
* [`ft_isalpha`](ft_libft/ft_isalpha.c)			- alphabetic character test.
* [`ft_islower`](ft_libft/ft_islower.c) *	- lower-case character test.
* [`ft_isupper`](ft_libft/ft_isupper.c) *	- upper-case character test.
* [`ft_isdigit`](ft_libft/ft_isdigit.c)			- decimal-digit character test.
* [`ft_isprint`](ft_libft/ft_isprint.c)			- printing character test (space character inclusive).
* [`ft_tolower`](ft_libft/ft_tolower.c)			- upper case to lower case letter conversion.
* [`ft_toupper`](ft_libft/ft_toupper.c)			- lower case to upper case letter c

### Functions from `<stdlib.h>` library

* [`ft_atoi`](ft_libft/ft_atoi.c)		- convert ASCII string to integer.
* [`ft_calloc`](ft_libft/ft_calloc.c)	- memory allocation.

### Functions from `<strings.h>` library

* [`ft_bzero`](ft_libft/ft_bzero.c)		- write zeroes to a byte string.
* [`ft_memset`](ft_libft/ft_memset.c)		- write a byte to a byte string.
* [`ft_memchr`](ft_libft/ft_memchr.c)		- locate byte in byte string.
* [`ft_memcmp`](ft_libft/ft_memcmp.c)		- compare byte string.
* [`ft_memmove`](ft_libft/ft_memmove.c)	- copy byte string.
* [`ft_memcpy`](ft_libft/ft_memcpy.c)		- copy memory area.
* [`ft_memccpy`](ft_libft/ft_memccpy.c)	- copy string until character found.


### Functions from `<string.h>` library

* [`ft_strlen`](ft_libft/ft_strlen.c)				- find length of string.
* [`ft_strchr`](ft_libft/ft_strchr.c)				- locate character in string (first occurrence).
* [`ft_strrchr`](ft_libft/ft_strrchr.c)			- locate character in string (last occurence).
* [`ft_strcmp`](ft_libft/ft_strcmp.c) *		- compare strings.
* [`ft_strncmp`](ft_libft/ft_strncmp.c) *			- compare strings (size-bounded).
* [`ft_strdup`](ft_libft/ft_strdup.c)				- save a copy of a string (with malloc).
* [`ft_strlcpy`](ft_libft/ft_strlcpy.c)			- size-bounded string copying.
* [`ft_strlcat`](ft_libft/ft_strlcat.c)			- size-bounded string concatenation.

### Non-standard functions

* [`ft_putchar_fd`](ft_libft/ft_putchar_fd.c)		- output a character to given file
* [`ft_putstr_fd`](ft_libft/ft_putstr_fd.c)		- output string to given file.
* [`ft_putendl_fd`](ft_libft/ft_putendl_fd.c)		- output string to given file with newline.
* [`ft_putnbr_fd`](ft_libft/ft_putnbr_fd.c)		- output integer to given file.
* [`ft_itoa`](ft_libft/ft_itoa.c)					- convert integer to ASCII string.
* [`ft_substr`](ft_libft/ft_substr.c)				- extract substring from string.
* [`ft_strtrim`](ft_libft/ft_strtrim.c)			- trim beginning and end of string with the specified characters.
* [`ft_strjoin`](ft_libft/ft_strjoin.c)			- concatenate two strings into a new string (with malloc).
* [`ft_split`](ft_libft/ft_split.c)				- split string, with specified character as delimiter, into an array of strings.
* [`ft_strmapi`](ft_libft/ft_strmapi.c)			- create new string from modifying string with specified function.
