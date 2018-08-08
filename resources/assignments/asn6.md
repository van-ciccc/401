# Assignment 6

## Exercise 00: libvc

|   Turn-in files   | libvc_creator.sh, vc_swap.c, vc_putstr.c, vc_strlen.c, vc_strcmp.c |
| :---------------: | :----------------------------------------------------------------: |
| Allowed functions |                               write                                |

- Create your vc library. It'll be called libvc.a

- A shell script called libvc_creator.sh will compile source files appropriately and will create your library.

- This library should contain _all_ of the following functions:
  ```c
  void vc_swap(int *a, int *b);
  void vc_putstr(char *str);
  int vc_strlen(char *str);
  int vc_strcmp(char *s1, char *s2);
  ```
- We'll run the following command-line:
  `$ bash libvc_creator.sh`

## Exercise 01: vc_print_program_name

|   Turn-in files   | vc_print_program_name.c |
| :---------------: | :---------------------: |
| Allowed functions |         printf          |

- We're dealing with a program here, you should therefore have a function _main_ in your .c file.

- Create a program that displays its own program name.

- Example:
  ```sh
  $ ./a.out
  ./a.out
  ```

## Exercise 02: vc_print_params

|   Turn-in files   | vc_print_params.c |
| :---------------: | :---------------: |
| Allowed functions |      printf       |

- We're dealing with a program here, you should therefore have a function _main_ in your .c file.

- Create a program that displays its given arguments.

- Example:
  ```sh
  $ ./a.out test1 test2 test3
  test1
  test2
  test3
  ```

## Exercise 03: vc_rev_params

|   Turn-in files   | vc_rev_params.c |
| :---------------: | :-------------: |
| Allowed functions |     printf      |

- We're dealing with a program here, you should therefore have a function _main_ in your .c file.

- Create a program that displays its given arguments in reverse order.

- It should display all arguments, except for _argv[0]_.

- All arguments have to have their own line.

## Exercise 04: vc_sort_params

|   Turn-in files   | vc_sort_params.c |
| :---------------: | :--------------: |
| Allowed functions |      printf      |

- We're dealing with a program here, you should therefore have a function _main_ in your .c file.

- Create a program that displays its given arguments sorted by ascii order.

- It should display all arguments, except for _argv[0]_.

- All arguments have to have their own line.
