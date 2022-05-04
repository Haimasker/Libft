<h1 align="center">
	libft
</h1>

<p align="center">
	This project was made in accordance with the project of School 21 (Ecole 42).
</p>

<p align="center">
	<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/haimasker/libft?color=blue" />
	<img alt="Number of lines of code" src="https://img.shields.io/tokei/lines/github/haimasker/libft?color=blue" />
	<img alt="Code language count" src="https://img.shields.io/github/languages/count/haimasker/libft?color=blue" />
	<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/haimasker/libft?color=blue" />
</p>

<h3 align="center">
	<a href="#preamble">Preamble</a>
	<span> · </span>
	<a href="#installation">Installation and usage</a>
	<span> · </span>
	<a href="#functions">Libft functions</a>
	<span> · </span>
	<a href="#testing">Testing</a>
</h3>

---

<a name="preamble"></a>
## Preamble

The purpose of this project is to create own C library that implements original functions from the standard library.

You can see the subject here: [Libft](en.subject.pdf).

Main requirements, rules and code style: [Norm](en_norm.pdf).

---

<a name="installation"></a>
## Installation and usage

Makefile compiles given functions into C static library file.

Compiler: `gcc`

Flags: `-Wall` `-Werror` `-Wextra`

<br>


* Go to the project folder:

```shell
$ cd 'path_to_libft'
```
* Then typo one of these command:

| Command         | Description                        |
| --------------- | ---------------------------------- |
| ``make``        | compiling mandatory part           |
| ``make bonus``  | compiling mandatory and bonus part |
| ``make clean``  | clearing all .o files              |
| ``make fclean`` | clearing all .o files and library  |

* To use compiled project in your code just include library header:

```c
#include "libft.h"
```

* While compiling your code add these flags:

```shell
-lft -L 'path_to_libft.a' -I 'path_to_libft.h'
```

---

<a name="functions"></a>
## Libft functions

| Libc functions                     | Additional functions                     | Bonus part                                   |
| ---------------------------------- | ---------------------------------------- | -------------------------------------------- |
| [ft_isalpha](/libft/ft_isalpha.c)  | [ft_substr](/libft/ft_substr.c)          | [ft_lstnew](/libft/ft_lstnew.c)              |
| [ft_isdigit](/libft/ft_isdigit.c)  | [ft_strjoin](/libft/ft_strjoin.c)        | [ft_lstadd_front](/libft/ft_lstadd_front.c)  |
| [ft_isalnum](/libft/ft_isalnum.c)  | [ft_strtrim](/libft/ft_strtrim.c)        | [ft_lstsize](/libft/ft_lstsize.c)            |
| [ft_isascii](/libft/ft_isascii.c)  | [ft_split](/libft/ft_split.c)            | [ft_lstlast](/libft/ft_lstlast.c)            |
| [ft_isprint](/libft/ft_isprint.c)  | [ft_itoa](/libft/ft_itoa.c)              | [ft_lstadd_back](/libft/ft_lstadd_back.c)    |
| [ft_strlen](/libft/ft_strlen.c)    | [ft_strmapi](/libft/ft_strmapi.c)        | [ft_lstdelone](/libft/ft_lstdelone.c)        |
| [ft_memset](/libft/ft_memset.c)    | [ft_striteri](/libft/ft_striteri.c)      | [ft_lstclear](/libft/ft_lstclear.c)          |
| [ft_bzero](/libft/ft_bzero.c)      | [ft_putchar_fd](/libft/ft_putchar_fd.c)  | [ft_lstiter](/libft/ft_lstiter.c)            |
| [ft_memcpy](/libft/ft_memcpy.c)    | [ft_putstr_fd](/libft/ft_putstr_fd.c)    | [ft_lstmap](/libft/ft_lstmap.c)              |
| [ft_memmove](/libft/ft_memmove.c)  | [ft_putendl_fd](/libft/ft_putendl_fd.c)  |                                              |
| [ft_strlcpy](/libft/ft_strlcpy.c)  | [ft_putnbr_fd](/libft/ft_putnbr_fd.c)    |                                              |
| [ft_strlcat](/libft/ft_strlcat.c)  |                                          |                                              |
| [ft_toupper](/libft/ft_toupper.c)  |                                          |                                              |
| [ft_tolower](/libft/ft_tolower.c)  |                                          |                                              |
| [ft_strchr](/libft/ft_strchr.c)    |                                          |                                              |
| [ft_strrchr](/libft/ft_strrchr.c)  |                                          |                                              |
| [ft_strncmp](/libft/ft_strncmp.c)  |                                          |                                              |
| [ft_memchr](/libft/ft_memchr.c)    |                                          |                                              |
| [ft_memcmp](/libft/ft_memcmp.c)    |                                          |                                              |
| [ft_strnstr](/libft/ft_strnstr.c)  |                                          |                                              |
| [ft_atoi](/libft/ft_atoi.c)        |                                          |                                              |
| [ft_calloc](/libft/ft_calloc.c)    |                                          |                                              |
| [ft_strdup](/libft/ft_strdup.c)    |                                          |                                              |

---

<a name="testing"></a>
## Testing

* You can check code norm due to [norminette](https://github.com/42School/norminette).

* These are some testers for ``libft`` project:

	* [libftTester](https://github.com/Tripouille/libftTester)

	* [Libftest](https://github.com/jtoty/Libftest)

	* [libft-war-machine](https://github.com/y3ll0w42/libft-war-machine)
