This editor was written in K&R C, please don't use ANSI C comments, function prototypes and other
ANSI features because then it won't compile anymore on decade old machines. Test modifications
with clang -std=c89 to avoid such things.

This is the only vi like editor usable on CP/M-80. If you feel the urge to add features consider a fork,
because if the size of the binary grows some, it becomes useless again on old 8-bit machines.