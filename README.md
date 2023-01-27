# donut-math
Donut math is a program which written with C, and I get this program from video clip reels on Instagram. When I search the source code of the program, i find this on a1k0n.net. But when I compile this using gcc on WSL2, the speed is too high. So I wanna decrease the speed, and then i push on this repository. Enjoy!

## How to Use in Kali Linux
Btw i using Kali Linux on Windows (WSL2), but I think u can compile this code on all Linux environments. So let me tell u how to use in Linux environment.
1. $ ``sudo apt update``
2. $ ``sudo apt upgrade``
3. $ ``sudo apt install build-essential gdb``
4. Run the follwing command: $ ``whereis gcc`` or $ ``whereis g++`` or $ ``whereis gdb``, to verify that they are installed.
<!-- 5. Create a file with .c typefile. For example: $ ``math.c`` -->
5. $ ``git clone https://github.com/anonimuslim/donut-math.c``
<!-- 6. Run using the following command: $ ``gcc filename.c -o filename -ls``, for example: $ ``gcc math.c -o math -ls`` -->
6. $ ``cd donut-math``
<!-- 7. Ignore the error on your terminal. -->
7. $ ``gcc math.c -o math`` or $ ``gcc math.c -o math -lm``
<!-- 8. And then, run the following command: $ ``./filename``, for example $ ``./math"`` -->
8. Ignore the error on your terminal.
9. $ ``./math``
10. Enjoy!

Note: Please create issue if u find the correct of this readme file.

## Reference
Source Code by: https://www.a1k0n.net/2011/07/20/donut-math.html

## My Tab when I met some error while compiling :v
- https://www.a1k0n.net/2011/07/20/donut-math.html
- https://largecats.github.io/blog/2019/09/22/run-c-from-wsl-in-vs-code/
- https://linuxhint.com/fix-shell-script-permission-denied-linux/
- https://stackoverflow.com/questions/18906190/why-am-i-getting-this-error-data-definition-has-no-type-or-storage-class
- https://codebeautify.org/c-formatter-beautifier
- https://www.onlinegdb.com/online_c_compiler
- https://www.programiz.com/c-programming/online-compiler/
- https://www.programiz.com/cpp-programming/online-compiler/
- https://frama-c.com/2011/07/22/Animated-donut-verification.html
- https://www.a1k0n.net/2006/09/15/obfuscated-c-donut.html
- https://www.youtube.com/watch?v=rj7DOPPTkQA
- https://www.dropbox.com/s/79ga2m7p2bnj1ga/donut_deobfuscated.c?dl=0
- https://github.com/craftvscruft/refactoring-donut/blob/refactor/donut.c
- https://vitux.com/how-to-write-and-run-a-c-program-in-linux/
