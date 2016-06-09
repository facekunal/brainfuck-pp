# brainfuck++

A toy brainfuck interpreter written in C++. I wrote this as a learning exercise
to understand pointers. You can read about it [here][blog-post].

## To Build

You need GCC.

    make

## Run It

```
./brainfuck -e ">++++++++[<+++++++++>-]<.>>+>+>++>[-]+<[>[->+<<++++>]<<]>.+++++++..+++.>
>+++++++.<<<[[-]<[-]>]<+++++++++++++++.>>.+++.------.--------.>>+.>++++."
Hello World!
./brainfuck hello.b
Hello World!
```

## Run a Brainfuck program as a script

```
#! /usr/local/bin/brainfuck
>++++++++[<+++++++++>-]<.>>+>+>++>[-]+<[>[->+<<++++>]<<]>.+++++++..+++.>
>+++++++.<<<[[-]<[-]>]<+++++++++++++++.>>.+++.------.--------.>>+.>++++.
```

```
chmod +x script.b
/script.b
Hello World!
```

[blog-post]: http://zacstewart.com/2013/09/15/learning-cpp-a-brainfuck-interpreter.html
