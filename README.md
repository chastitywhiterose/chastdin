# chastdin

An interactive stack based calculator written in Assembly and C that reads from stdin, also known as the keyboard.

chastdin is a fork of chastack which used the command line arguments passed to run the program. This program provides an alternative interface and also adds more commands.

The ultimate purpose of this calculator is to refine my string processing functions as part of the chastdin library. The most important function in this library is "getstring" which reads a string until a whitespace character is found.

Using this library, other programs like chastehex,chastecmp,and chastext can be ported over to using standard input. When these versions are written, they would be postfixed with "-stdin" such as "chastehex-stdin".

The second purpose of this calculator is to allow teaching people how a postfix calculator works. By recording videos I will probably explain more to wider audiences about the behavior of this calculator and other tools like GNU dc.
