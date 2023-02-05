# Libft
Libft is the first School 21 project and its purpose is to implement some of standart C functions and write additional ones which will be used in next C projects.
___
## Functions of the library
#### Libc functions
 - ft_atoi
 - ft_bzero
 - ft_calloc
 - ft_isalnum
 - ft_isalpha
 - ft_isascii
 - ft_isdigit
 - ft_isprint
 - ft_memccpy
 - ft_memchr
 - ft_memcmp
 - ft_memcpy
 - ft_memmove
 - ft_memset
 - ft_strchr
 - ft_strlcat
 - ft_strlcpy
 - ft_strlen
 - ft_strncmp
 - ft_strnstr
 - ft_strrchr
 - ft_tolower
 - ft_toupper
#### Additional functions
 - char \*`ft_itoa`(int n) - allocates and returns a string
representing the integer received as an argument.
 - void `ft_putchar_fd`(char c, int fd) - outputs the character ’c’ to the given file descriptor.
 - void `ft_putstr_fd`(char \*s, int fd) - outputs the string ’s’ to the given file descriptor.
 - void `ft_putendl_fd`(char \*s, int fd) - outputs the string ’s’ to the given file descriptor, followed by a newline.
 - void `ft_putnbr_fd`(int n, int fd) - outputs the integer ’n’ to the given file descriptor
 - char	\*\*`ft_split`(char const \*s, char c) - allocates and returns an array of strings obtained by splitting ’s’ using the character ’c’ as a delimiter. The array ends by a NULL pointer.
 - char \*`ft_strjoin`(char const \*s1, char const \*s2) - allocates and returns a new string, which is the result of the concatenation of ’s1’ and ’s2’.
 - char \*`ft_strtrim`(char const \*s1, char const \*set) - allocates and returns a copy of ’s1’ with the characters specified in ’set’ removed from the beginning and the end of the string.
 - char	\*`ft_strdup`(const char \*s1) - allocates sufficient memory for a copy of the string s1, does the copy, and returns a pointer to it.
 - char	\*`ft_strmapi`(char const \*s, char (\*f)(unsigned int, char)) - applies the function ’f’ to each character of the string ’s’ , and passing its index as first argument to create a new string resulting from successive applications of ’f’.
 - char \*`ft_substr`(char const \*s, unsigned int start, size_t len) - allocates and returns a substring from the string ’s’. The substring begins at index ’start’ and is of
maximum size ’len’.
#### Bonus funstions
These ones works with the following strust
 ```
typedef struct s_list
{
	void			*content;
	struct s_list	*next;
}				t_list;
 ```
I don't find it really useful, but the subject required them.
 - ft_lstadd_back
 - ft_lstadd_front
 - ft_lstclear
 - ft_lstdelone
 - ft_lstiter
 - ft_lstlast
 - ft_lstmap
 - ft_lstnew
 - ft_lstsize
