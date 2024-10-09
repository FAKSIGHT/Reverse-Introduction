# Reverse-Introduction

### Simple variable 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_variable.c -o simple_variable.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_variable.c -o simple_variable
```

### Simple arithmetic

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_arithmetic.c -o simple_arithmetic.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_arithmetic.c -o simple_arithmetic
```

### Simple function call 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_function_call.c -o simple_function_call.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_function_call.c -o simple_function_call
```

### Simple if 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_if.c -o simple_if.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_if.c -o simple_if
``` 

### Simple While 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_while.c -o simple_while.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_while.c -o simple_while
``` 

### Simple do-while 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_do_while.c -o simple_do_while.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_do_while.c -o simple_do_while
```

### Simple switch 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_switch.c -o simple_switch.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_switch.c -o simple_switch
```

### Simple for 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_for.c -o simple_for.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_for.c -o simple_for
```

### Simple array 

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_array.c -o simple_array.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_array.c -o simple_array
```

### Simple recursive

```bash
gcc -m32 -O0 -fno-asynchronous-unwind-tables -S simple_recursive.c -o simple_recursive.s
gcc -m32 -O0 -fno-asynchronous-unwind-tables simple_recursive.c -o simple_recursive
```